# ubuntu18_starter
ansible playbook to set up ubuntu18

## Getting Started

```shell
ansible-playbook -i inventories/development provision.yml --diff -v -K
```

### Prerequisites

* Environment to run ansible playbook
    - [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)


## Running the tests

```shell
ansible-playbook -i inventories/development provision.yml --diff -v -K --check
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details