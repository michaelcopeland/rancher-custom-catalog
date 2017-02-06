# Strongswan for Docker

Strongswan for Docker.

I had to update the ports as Rancher ipsec runs on 500 & 4500 by default. See below:

Ports (container:host):
- 1500:500/udp
- 14500:4500/udp
- 11701:1701/udp