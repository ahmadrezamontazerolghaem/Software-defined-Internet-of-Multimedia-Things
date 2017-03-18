VoIP is becoming a low priced and efﬁcient replacement for
PSTN in communication industries.
With a widely growing application,
SIP is an application layer signaling protocol which has been standardized
by IETF for creating, modifying, and terminating VoIP sessions.
Generally speaking, this protocol routes a call request to its destination
by using SIP proxies. With the increasing use of SIP, traditional conﬁgurations
pose certain drawbacks, such as ineffective routing, unoptimized
management of proxy resources (including CPU and memory), and an
overload condition. The current paper presents three novel approaches,
namely OpenSIP(s),
for the purpose of upgrading the SIP network
framework with new technologies, such as SDN and NFV. SDN provides
for predominant management by decoupling data and control planes
alongside
a software-based central control (or softwarization). This, in
turn, results in effective routing and resource management. Moreover,
NFV assists SDN by virtualizing various devices and functions. However,
current SDN elements limit the inspected ﬁelds to layer 2-4 headers,
whereas SIP routing information is in the layer 7 header. OpenSIP(s)
enforces policies
on SIP networking agnostic to higher layers with the aid
of the DPI engine. Among the beneﬁts of OpenSIP is programmability,
cost reduction, uniﬁed management,
routing, as well as efﬁcient load
balancing. The present study implements OpenSIP(s) on a real testbed
which includes Open vSwitch and the Floodlight controller. The results
show that the proposed architectures have
a low overhead and satisfactory
performance and, in addition, can take advantage of a ﬂexible scale-out
design for application deployment.
