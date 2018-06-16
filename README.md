# computer-network
## 第一章 引言
1，“计算机网络”来表示一组通过单一技术相互连接的自主计算机集合。如果两台计算机能够交换信息， 则称这两台计算机是相互连接的（interconnected）。

2，计算机网络和分布式系统（distributed system）这两个概念容易使人混淆。两者的关键差别在于：

>由一组独立计算机组成的分布式系统呈现给用户的是一个关联系统。一般来说，在用户看来，分布式系统只是一个模型或范型。通常在操作系统之上有一层软件负责实现这个模型，这个软件就称为中间件（middleware）。最著名的分布式系统例子是万维网（World Wide Web）。万维网运行在Internet 之上，这个模型的所有一切都表现得像是一个文档（Web 页面）一样。

>在计算机网络中，这种一致性、模型以及软件都不存在。用户看到的是实际的机器，系统并没有努力使这些机器看起来一样，或者试图使它们的行为保持一致。如果机器有不同的硬件或者不同的操作系统，那么这些差异对于用户来说是完全可见的。如果一个用户希望在一台远程机器上运行一个程序，则他必须首先登录到远程机器上，然后在那台机器上运行该程序。

>实际上，分布式系统是建立在网络之上的软件系统。这个软件给予分布式系统以高度的凝聚力和透明性。因此，网络与分布式系统之间的区别在于软件（特别是操作系统），而不是硬件。然而，这两个主题之间有相当多的重叠。例如，分布式系统和计算机网络都需要移动
文件。不同之处在于由谁来发起移动行为，是系统还是用户？

3, 虚拟专用网络（VPN，Virtual Private Networks）的网络技术可以将不同地点的单个网络联结成一个扩展的网络。概括地来说，VPN 的目标是试图终结“地理位置的束缚”。

4, 关于计算机网络，没有一种被普遍接受的分类方法，但是有两个维度非常重要：传输技术和网络尺度:

从广义上讲，目前普遍使用的传输技术有两种，分别是**广播式链路和点到点链路**：见正文13页（27/753）

5，个域网（PAN，Personal Area Network）：蓝牙，RFID；

局域网（LAN，Local Area Network）：在这些系统中，每台计算机都有一个无线调制解调器和一个天线，用来与其他计算机通信。在大多数情况下，每台计算机与安装在天花板上的一个设备通信，这个设备，称为接入点（AP，Access Point）、无线路由器（wireless router）或者基站（base station），它主要负责中继无线计算机之间的数据包，还负责中继无线计算机和Internet 之间的数据包。无线局域网的一个标准称为IEEE 802.11，俗称为WiFi，已经被非常广泛地使用。它在任何地方可以从11 Mbps 到几百个Mbps 的速率运行（我们在本书中将沿用传统的线路测量速率：1 Mbps（兆比特/秒）等于1 000 000 比特/秒；1 Gbps（吉比特/秒）等于1 000 000 000
比特/秒。

**以太网（Ethernet）的IEEE802.3 是迄今为止最常见的一种有线局域网。**

6，一个交换机有多个端口（port），每个端口连接一台计算机。交换机的工作是中继与之连接的计算机之间的数据包，根据每个数据包中的地址来确定这个数据包要发送给哪台计算机。



