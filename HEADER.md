# Nginx-project for ansible

[![Integration](https://github.com/practical-ansible/nginx-project/workflows/CI/badge.svg)](https://github.com/practical-ansible/nginx-project/actions)
[![Quality](https://img.shields.io/ansible/quality/48836.svg)](https://galaxy.ansible.com/practical-ansible/nginx_docker)
[![Downloads](https://img.shields.io/ansible/role/d/48836.svg)](https://galaxy.ansible.com/practical-ansible/nginx_docker)
[![Role](https://img.shields.io/ansible/role/48836)](https://galaxy.ansible.com/practical-ansible/nginx_docker)

This is a base for all practical-ansible nginx roles. It does only initial configuration, like create working directory for the project and obtain SSL certificate. Try other roles that depend on this one:

* [nginx_static](https://github.com/practical-ansible/nginx-static)
* [nginx_docker](https://github.com/practical-ansible/nginx-docker)

## Features

* Creates living space for the project on your server
* Obtains Let's Encrypt SSL certificate
* Configures Nginx to display a simple static HTML page
* Ready to be extended - does not overwrite nginx configuration

## Prerequisities

* Target user with rights to config nginx

## Install

```shell
ansible-galaxy install practical-ansible.nginx_project
```

# Reference manual
