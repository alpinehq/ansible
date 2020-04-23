# ansible

![ansible](https://github.com/alpinehq/ansible/workflows/ansible/badge.svg)

This repo is all the ansible playbooks to configure alpinehq servers, most likely set up by [alpinehq/infrastructure](https://github.com/alpinehq/infrastructure)

# Usage

```bash
$ python3 -m pip install virtualenv
$ python3 -m virtualenv .venv
$ source .venv/bin/activate
(.venv) $ pip install -U ansible
(.venv) $ echo "THE PASSWORD" > .pass
(.venv) $ ansible-playbook web.yml
```
