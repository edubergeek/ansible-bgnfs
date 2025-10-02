# Infrastructure as Code (IAC) using Ansible and Beegfs Storage
Deploy a beegfs client compatible with [Ansible Beegfs Service using Docker Compose](https://github.com/edubergeek/ansible-beegfs)

**Author** Curt Dodds
**Organization** Institute for Astronomy, University of Hawaii, Manoa
**Date** 2025-10-02

## Playbooks
- beegfs-prep.yaml
    - Install all prerequisites for Beegfs client
- beegfs-client.yaml
    - Install the Beegfs client
- beegfs-up.yaml
    - Run the Beegfs client
- beegfs-down.yaml
    - Stop the Beegfs client
