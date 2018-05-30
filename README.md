# quagga-bgp-netgen
Generate a Quagga/FRR bgp configuration file with lot's of routes.
Allows to use Quagga/FRR as simple BGP routes generator on a lab.

Example of usage:
```
quagga-bgp-netgen [nets-number] [local-as] [router-id] [remote-as] [remote-peer-ip]
example:
quagga-bgp-netgen 400000 100 0.0.0.100 200 10.0.0.2 > /usr/local/etc/frr/bgpd.conf
```

