## Ansible

### Overview

This repository is a result of my exploration of Ansible, a powerful automation tool. I created this playbook to automate nginx installation for learning purpose (can be used in prodution also, limited to nginx installation)

### Environment Details

- Ansible 2.16.1
- Python 3.9.6

### Usage

Clone this repository to your local machine. Command to run the playbook: `ansible-playbook install-nginx.yaml -i hosts.yaml --extra-vars "host=home_server" --ask-become-pass`.
**Remember** to modify the hosts.ymal as per your configuration.

### Contributing

Feel free to contribute to this repository by opening issues, providing feedback, or submitting pull requests. Your contributions are highly appreciated!

### License

This Ansible Nginx Automation Repository is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license.

**Happy automating!**
