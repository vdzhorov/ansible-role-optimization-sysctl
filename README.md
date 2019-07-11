# ansible-role-optimization-sysctl

Ansible role for general sysctl optimization

### Prerequisites

* Make sure that you understand what the variables in the settings do.

### Supported OS

* CentOS 7

## Deployment

Example playbook named optimization-sysctl.yml:

```
- hosts: web
  roles:
    - 'ansible-role-optimization-sysctl'
```

Configure your vars in vars/main.yml. After that simply run your playbook:

```
ansible-playbook -i '<TARGET_HOST_IP>,' playbooks/optimization-sysctl.yml
```

## Built With

* [Ansible 2.8](https://docs.ansible.com/ansible/2.8/index.html)

## Authors

* **Valentin Dzhorov** - *Initial work* - [vdzhorov](https://github.com/vdzhorov)

## Company

* **Delta.BG**

## License

This project is licensed under the MIT License.
