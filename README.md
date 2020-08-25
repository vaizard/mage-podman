# mage-podman

An Ansible role to install podman.

NOTE: When deploying podman in a nested container, you may need to set 
  - security.nesting: true
  - security.privileged: true
This comes with security issues you should make yourself aware about.
See i.e. https://ubuntu.com/blog/nested-containers-in-lxd
