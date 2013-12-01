# ansible playbooks

Right now, this is just a test playbook for setting up
a mail server.

## mailserver

Sets up a simple mail server configuration on debian wheezy.

* `postfix` as MTA
* `fetchmail` to pop mail from other accounts into this one
* `dovecot` for IMAP access

Right now, there is no spam control at all, and it's mostly untested.

Use at your own risk.

