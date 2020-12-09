# ansible-lgsm
quick ansible module for linuxgsm install.  defaults to installing csgo

Example playbook:
```
---
- name: Setup CS:GO Server
  hosts: all
  become: yes

  roles:
    - ansible-lgsm
```
