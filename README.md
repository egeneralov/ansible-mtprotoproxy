egeneralov.mtprotoproxy
=========

Deploy non-official python telegram proxy server.

Requirements
------------

Any systemd-powered system.

WARNING
-------

Role will manage iptables (only for proxy port and e/r connections).

Role Variables
--------------

- proxy_port
- secret
- adtag (optional)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: egeneralov.mtprotoproxy, proxy_port: 3256, secret: 0123456789abcdef0123456789abcdef }

License
-------

MIT

Author Information
------------------

Eduard Generalov <eduard@generalov.net>

	say { echo "Working in $1, fucking $1."; }
	say mail.ru
