phpipam-pythonlib
=================

Python Library for PHPIPAM API 

Tested on API v0.9

<b>Note:</b> There is a known problem with the API implementation of Subnets::createSubnets() in v0.9 of the API. You will not be able to create new subnets unless you modify the following file: <https://github.com/enovance/phpipam/blob/master/api/models/subnet.php>. Hopefully these issues will be addressed in the next release. 

<h4>Requirements</h4>
Python Rijndael AES implmementation: <http://fastcrypto.org/umac/2004/src/rijndael.py>

<h4>Usage</h4>

<pre>
ipam = PHPIPAM("phpipam.example.com", "api_id", "api_key")
print ipam.read_sections()
</pre>
