8 blocks at 16bit -> 8 x 4 blocks Hex

Leading 0 are removed

0000 can be shortend

Subnetmasks like [[IPv4]]


Unicast
One receiver

Multicast
Group of receivers

Anycast
Unicast to a group of NICs

Addresses:

Loopback ::1/128
Unspecified ::/128
Link-Local :: fe80 ::/10
Global 2000::/3
Unique local fc00::/7
Embedded IPv4 ::ffff:([[IPv4]])

Multicast ff00::/8
1) Assigned MC for predefined Groups from IFs (like [[IPv4]])
	FF02::1 all IPv6-Nics
	FF02::2 all Router
2) Solicited node MC
	 FF02::1:FFxx:xxxx (last 6 hex of IPv6 unicast address)
	 last 6 hex also get applied to multicast mac: 33:33:xx:xx:xx
