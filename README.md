plumelo.letsencrypt
=========

Ansible role to generate and install SSL certificates from Letsencrypt


Variables
--------------

    letsencrypt_email: ""
    letsencrypt_domains: []
    letsencrypt_cron: True
    letsencrypt_cron_actions: []
    letsencrypt_challenge: 'tls-sni-01'

Usage
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - plumelo.letsencrypt

