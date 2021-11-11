# Provisioning a container image using Ansible-Bender

Requirements

- [ansible](https://www.ansible.com/)
- [ansible-bender](https://ansible-community.github.io/ansible-bender/build/html/index.html)
- [Podman](https://podman.io/)
- [Buildah](https://buildah.io/)

## Installation

```bash
dnf -y install python310 ansible buildah podman
```

or

```bash
pip3 install ansible
```

```bash
pip3 install ansible-bender
```

Create ansible-bender bash alias

```bash
alias ab="ansible-bender"
```
