A-Select authentication module for Drupal
=========================================

About
-----
This Drupal module provides a clean native implementation for authentication using the A-Select protocol, without requiring an agent or httpd module of some sorts.
This will come in handy for those not able or not wanting to run Apache 1.3/2.0 with the ASelect module, or the A-Select agent.

Requirements
------------
- PHP >=5.0
  - OpenSSL extension enabled for message signing
  - pecl_http extension
- Drupal >=7.0
- Some kind of A-Select server (including app authorization) to authenticate to
