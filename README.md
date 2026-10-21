# Configuration Management
Homework reports for the **Configuration Management Systems** course, taught by Tero Karvinen. This repository documents hands on Linux administration and configuration automation utilizing **Ansible**, from managing users and services, to building repeatable system configurations.
> Course reports are written in Finnish.

## Homework reports

| Report                  | Topics                                                                      |
|-------------------------|-----------------------------------------------------------------------------|
| [**H1** Hei Ansiblen maailma](https://github.com/BlendiTH/Configuration-Management/blob/main/H1-Hei%20Ansiblen%20maailma.md) | SSH key authentication & first Ansible playbooks                            |
| [**H2** Voileipä](https://github.com/BlendiTH/Configuration-Management/blob/main/H2-Voileip%C3%A4.md)             | User accounts, sudo & file permissions and system settings                  |
| [**H3** Demoni](https://github.com/BlendiTH/Configuration-Management/blob/main/H3-Demoni.md)               | Apache and Nginx configuration, Ansible roles & service handlers            |
| [**H4** Pizza Fantasia](https://github.com/BlendiTH/Configuration-Management/blob/main/H4-Pizza%20Fantasia.md)       | Fail2Ban automation, service recovery & idempotence                         |
| [**H5** Gitar Hero](https://github.com/BlendiTH/Configuration-Management/blob/main/H5-Gitar%20Hero.md)           | Git, GitHub, SSH authentication and version control for configuration files |

## Final Project | [ezTool](https://github.com/Arsi-573/eztool)
A group project developed for the course: an Ansible-based configuration tool intended to simplify IT setup for small businesses.

The playbooks automate workstation setup, employee account creation, SSH keys, common system configuration and also a local intranet with the help of Caddy. The configuration is organised into reusable Ansible roles.

**Techologies:** Ansible, YAML, Bash, Linux, SSH, Git, Caddy and Jinja2
> **Disclaimer:** ezTool is a learning project, not production ready software. The projects README documents the setup process along with its security limitations.

## Technical Focus

The practical work covers writing Ansible playbooks and roles, managing different permissions and Linux users, deploying and configuring services, also restoring a system after configuration files or services have been changed or removed. The exercises also demonstrate idempotence: when a repeated playbook runs make no unnecessary changes when the system already matches the desired configuration.
