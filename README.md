## atmo-ansible-callback
==========

This is a reference implementation for an Ansible callback for Atmosphere.  It
minimally expects an extra vars called LOGNAME, which could be the uuid of the
instance. If LOGNAME does not exist, the callback does nothing. If an extra
vars named LOGFOLDER is provided, then it will use that path to create the log
file, rather than the the default path /var/log/ansible/hosts.  The log path
should exist.

This file should be placed one of the directories defined by the
callback_plugins in the ansible.cfg.  The system-wide setting is typically
pointed to /usr/share/ansible_plugins/callback_plugins.

## License

See LICENSE.txt for license information

Where the cloud lives!
