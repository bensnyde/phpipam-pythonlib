phpipam-pythonlib
=================

Python Library for PHPIPAM API 

Tested on API v0.9

There is a known problem with the API implementation of Subnets::createSubnets(). You will not be able to create new subnets unless you modify the PHP code. 

<h2>Usage</h2>

ipam = PHPIPAM("phpipam.example.com", "api_id", "api_key")
print ipam.read_sections()
