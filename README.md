cleanpuppetnodes
================

Overview
--------

This program cleans the following puppet node info: facts, node and certificate.


Installing
----------

You can install it simply running these commands on your puppetmaster:

# wget --no-check-certificate -O /usr/local/sbin/cleanpuppetnodes https://github.com/algodelinux/cleanpuppetnodes/raw/master/cleanpuppetnodes  
# chmod 755 /usr/local/sbin/cleanpuppetnodes  


Using
----------

You can use it without parameters an clean nodes older than predefined days:

# cleanpuppetnodes

Or specify maximun number days:

# cleanpuppetnodes 30


## Authors

- Esteban M. Navas Martín (algodelinux@gmail.com)
