## Cacti Templates
Templates are for http://cacti.net

`graph_cisco_aironet_two_radios.xml` is for Cisco Autonymous APs.  When creating a new AP host, I usually set `Host Template` to `Cisco Router`, then add this graph to the host in Cacti.

`graph_two_interfaces_stacked.xml` is a template I use for a device w/ more than one interface, and i want to see both interfaces overlaid.

Cacti and rrdtool seem to make stacking/aggregating multiple sources into one graph.

Both graphs were exported from 0.8.8b
