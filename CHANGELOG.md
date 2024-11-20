# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased] - 2024-11-20

### Added

- Initial project setup with Docker and Ansible configuration
- Basic workspace configuration
- Ansible playbook for PiCapsule provisioning
- Docker container setup for development environment
- increase swap size to 512MB

### Infrastructure

- Docker development environment with:
  - Python 3.10
  - Ansible core 2.11.10
  - Ansible lint 5.4.0
  - Support for SSH agent forwarding

### Dependencies

- ansible-core==2.11.10
- ansible-lint==5.4.0
- boto3==1.18.10
- botocore==1.21.10
- ansible.posix collection v1.3.0
- community.general collection v4.8.0
- marcomc.picapsule role

[Unreleased]: https://github.com/yourusername/picapsule-setup/compare/v0.0.0...HEAD
