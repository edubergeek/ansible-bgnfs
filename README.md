# Infrastructure as Code (IAC) Ansible + Beegfs
Deploy a beegfs client compatible with [Ansible Beegfs Service using Docker Compose](https://github.com/edubergeek/ansible-beegfs)

**Author** Curt Dodds

**Organization** Institute for Astronomy, University of Hawaii, Manoa

**Date** 2025-10-02

## Playbooks
- beegfs-prep.yaml
    - Install all prerequisites for Beegfs client
```
      ansible-playbook -i inventory.yaml nfs-prep.yaml)
```
- beegfs-client.yaml
    - Install the Beegfs client
```
ansible-playbook -i inventory.yaml beegfs-client.yaml
```
- beegfs-up.yaml
    - Run the Beegfs client
```
ansible-playbook -i inventory.yaml beegfs-up.yaml
```
- beegfs-down.yaml
    - Stop the Beegfs client
```
ansible-playbook -i inventory.yaml beegfs-down.yaml
```
