Subnet masking is where you divide the IP into two parts, one for the host, other for the network


10.0.0.0

255.0.0.0

means that 10 cannot be modified, but the rest can.

The reason? You're doing this subnet mask dependant upon how many devices you have in your household or place, each device needs an ip, therefore you may need to expand the network.


It only goes up to 256, 2 are already allocated, one for the [[Broadcast Address]] 192.168.0.255 and another for the (network address) 192.168.0.0