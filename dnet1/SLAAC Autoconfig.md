[[IPv6]]
- Host creates Link Local
- Host makes sure via [[Duplicated Address Detection (DAD)]] that his IP is unique
- Host sends a [[Router Solicitation Message]] at the Router Multicast Address (FF02::2) and asks for the Network Prefix. Router answers with [[Advertisment Message (ICMPv6)]]
- Host constructs a IPv6 address with prefix from router
- Host makes sure via [[Duplicated Address Detection (DAD)]] that his IP is unique
![[Pasted image 20250225102922.png]]