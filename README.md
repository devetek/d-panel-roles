## Description

List of roles that have been tested and work well in dPanel. Visit [dPanel](https://cloud.terpusat.com) to register your VM, create your `Ansible Playbook`, and execute the playbook on your machine.


### How it Works
First, the worker will retrieve prerequisite data (credentials, inventories, variables) from [dPanel](https://cloud.terpusat.com) using the token on the worker. Then, it will execute your playbook on the Virtual Machine or Kubernetes targets to carry out tasks defined in the playbook, such as installing databases, installing services, or deploying applications. The worker (GitHub Action, VM, Kube Pod) will first pull this repository as the base. After that, it installs dependencies and executes your playbook.