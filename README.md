# Qweebs Ansible

An Ansible playbook that covers the management of the https://qweebs.com keyboard store, including observability and backup capabilities.

Backups are handled by dumping the db and files into a directory on the host running the site (by a "sidecar" container), and then grabbing that repository from my NAS.

## Security

If you find a security anomaly in this playbook or on the site, please do not create an issue, but rather e-mail me at support@qweebs.com. Thank you.
