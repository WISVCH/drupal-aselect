ASelect authentication module for Drupal
========================================

About
-----
This Drupal module provides a clean native implementation for authentication using the ASelect protocol, without requiring an agent or httpd module of some sorts.
This will come in handy for those not able or not wanting to run Apache 1.3/2.0 with the ASelect module.

Requirements
------------
- PHP >=5.0
- Drupal >=6.0
- PHP OpenSSL module enabled for message signing
- Some kind of ASelect server (including app authorization) to authenticate to
