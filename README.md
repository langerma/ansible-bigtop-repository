# ansible-bigtop-repository
add apache bigtop repository

## [Example Playbook](#example-playbook)

add repository to all hosts
```yaml
---
- name: add bigtop repository
  hosts: all
  become: yes
  gather_facts: yes

  roles:
    - role: ansible-bigtop-repository
```