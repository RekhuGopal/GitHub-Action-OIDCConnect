---
- hosts: all
  become: yes
  tasks:
  - name: Install packages
    apt:
      name:
      - ntpdate
      state: latest
      cache_valid_time: 3600
