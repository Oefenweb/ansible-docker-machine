## docker-machine

[![CI](https://github.com/Oefenweb/ansible-docker-machine/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-docker-machine/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-docker--machine-blue.svg)](https://galaxy.ansible.com/oefenweb/docker_machine)

Set up (the latest or a specific version of) [Docker Machine](https://docs.docker.com/machine) in Debian-like systems.

#### Requirements

None

#### Variables

* `docker_machine_version` [default: `v0.16.2`]: Version to install
* `docker_machine_install_prefix` [default: `/usr/local/bin`]: Install prefix
* `docker_machine_download_url` [default: `https://github.com`]: Download url

## Dependencies

None

## Recommended

* `ansible-docker` ([see](https://github.com/Oefenweb/ansible-docker))
* `ansible-docker-compose` ([see](https://github.com/Oefenweb/ansible-docker-compose))

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.docker-machine
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-docker-machine/issues)!
