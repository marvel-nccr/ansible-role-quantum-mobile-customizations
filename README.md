[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-quantum-mobile-customizations.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-quantum-mobile-customizations)

# Ansible Role: marvel-nccr.quantum_mobile_customizations

An ansible role that customizes Ubuntu for [Quantum Mobile](https://github.com/marvel-nccr/quantum-mobile).

## Installation

`ansible-galaxy install marvel-nccr.quantum_mobile_customizations`

## Role Variables

See `defaults/main.yml`

## Example Playbook

```
- hosts: machines
  roles:
  - role: nccr-marvel.quantum_mobile_customizations
```

## Tests

This role uses [Molecule](https://molecule.readthedocs.io/en/latest/#) and
Docker for tests. Once Docker is installed, run tests using

```bash
pip install -r requirements.txt
molecule test
```

## License

MIT

## Contact

Please direct inquiries regarding Quantum Mobile and associated ansible roles to the [AiiDA mailinglist](http://www.aiida.net/mailing-list/).
