# p2p-
<p>WebRTC 应用包括下面四个主要的概念：
   信令服务器（Signalling servers） 用于在两个用户之间交换信息, 初始化连接 
   
   为参与点对点通信的两个浏览器之间交换会话描述协议（SDP）。SDP 包含浏览器的 RTP 媒体栈配置所需的全部信息，包括媒体类型（音频、视频、数据）、所需的编解码器，用于编解码器的哥哥参数或设置，以及有关带宽的信息。此外，信令通道还用于交换候选地址，以便进行 ICE 打洞。
   
   ICE 服务器（ICE servers） 交互式建立连接（ICE）是一种标准穿透协议, 让位于 NAT 之后的两个浏览器之间能直接发送和接收数据包 
   
   STUN: STUN（Simple Traversal of UDP over NATs，NAT 的UDP简单穿越）是一种网络协议，它允许位于NAT（或多重NAT）后的客户端找出自己的公网地址。 
   TURN: 在大多情况下，通过穿透可以建立直接对等连接。但是，若 NAT 或防火墙限制非常严格，无法建立连接，就只能通过 TURN 服务器中继媒体。
   
   媒体服务器 （Media servers） 媒体服务器不是必须的
   
   JavaScript 接口 （JavaScript API）</p>