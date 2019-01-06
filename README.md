# ansiblemyfedora
Bootstrap a Fedora workstation using Ansible from scratch

## Pre-requisite

```
sudo dnf install ansible
```

## Clone this repo

```
git clone https://github.com/silefort/ansiblemyfedora.git
cd ansiblemyfedora
```

## Deploy

```
ansible-playbook --connection=local --inventory=127.0.0.1, playbook.yml -K -b
```

## Manual setups


