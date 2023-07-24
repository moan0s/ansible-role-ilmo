# 📚 [ILMO](https://github.com/moan0s/ILMO2/) Ansible Role

![Ilmo Logo](assets/logo.svg)

[ILMO](https://github.com/moan0s/ILMO2/)  is a self-hosted library management tool. This role helps you to set up ILMO:

- with everything run in [Docker](https://www.docker.com/) containers
- powered by [the official ilmo container image](https://hub.docker.com/r/moanos/ilmo/)


## Installing

To configure and install ILMO on your own server(s), you should use a playbook like [Mother of all self-hosting](https://github.com/mother-of-all-self-hosting/mash-playbook) or write your own.

# Configuring this role for your playbook

```
ilmo_enabled: true
ilmo_hostname: 'example.org'

ilmo_db_host:

ilmo_db_name:
ilmo_db_user:
ilmo_db_password:
```

## Support

- Github issues: [moan0s/ansible-role-ilmo/issues](https://github.com/moan0s/ansible-role-ilmo/issues)
