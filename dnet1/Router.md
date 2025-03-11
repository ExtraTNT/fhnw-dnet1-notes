[[Layer 2]] [[Layer 3]]
[[Hops]]

Has a [[RouterID]]

Header Stack

Http
Tcp
Ip
Eth

Can do [[NAT]]

Has a Routing table
Destination [[Subnet]], Weights (In case of multiple routes)
Does load-balancing 

Weight:
AD: Administrative Distance (selects smallest possible) -> more important than metric
Metric: Distance between routers (from protocol)Link-Local :: fe80 ::/10