# Manjaro/Arch Linux for Software Development, DevOps and ML
Rev up your productivity with ease! Transform your Manjaro or Arch Linux into a powerhouse for Software Development, DevOps, and Machine Learning with our streamlined Ansible playbook(s).

![molecule test](https://github.com/pgagarinov/manjaro-arch-dev-env-ansible/actions/workflows/ci.yml/badge.svg


Run the playbook with `-K` or `--ask-become-pass` (we need this for the very first run until at least 1st task setting sudo users access with no password is completed):
```
ansible-playbook -i ./inventory -v ./playbooks/install-4server-all.yml -K
```
or
```
ansible-playbook -i ./inventory-local -v ./playbooks/install-4server-all.yml -K
```

