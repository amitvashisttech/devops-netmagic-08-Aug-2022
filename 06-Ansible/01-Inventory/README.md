```
 2019  mkdir 01-Inventory
 2020  ls
 2021  cd 01-Inventory/
 2022  ls
 2023  vim hosts
 2024  ls
 2025  ansible all -i hosts -m ping -u vagrant -k
 2026  apt-get install sshpass -y
 2027  ansible all -i hosts -m ping -u vagrant -k
 2028  ssh vagrant@172.31.0.100
 2029  ansible all -i hosts -m ping -u vagrant -k
 2030  ssh vagrant@172.31.0.101
 2031  ssh vagrant@172.31.0.102
 2032  ls
 2033  cat /root/.ssh/known_hosts
 2034  ansible all -i hosts -m ping -u vagrant -k
```
