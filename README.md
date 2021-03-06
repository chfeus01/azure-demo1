# Palo Alto Networks LB Sandwitch for Azure Egress Security

[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fchfeus01%2Fazure-demo1%2Fmaster%2FazureDeploy.json)

This template automates deployment of firewall LB sandwich environment for Egress Security.
It includes following components:

- One Internal Load Balancer (LB-Egress) - "Standard SKU"
- Two Palo Alto Networks Firewalls
- One Ubuntu Server to test outbound traffic
- Multiple Subnets and UDRs to support the traffic flow

 The template allows selection of:
 - New or Existing VNET
 - Bootstraping
 - BYOL or PAYG Licensing
 and creates all the infrastructure and appropriate UDRs.
 
 If bootstraping with default configuration file is used default credentials are:
 - Username: paloalto
 - Password: PaloAlt0!123!!
