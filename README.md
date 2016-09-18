
# future-gateway-api-server

Docker container for the FG API server.

# Building the container

  1. The container should be built using an Ansible playbook
  1. This container uses the [AAROC DevOps repo](https://github.com/AAROC/DevOps), which has the Ansible playbook in it.
  1. The following command should be run to build the container :
        ```bash
           docker build -v $PWD/../../../Ansible/:/root/DevOps/Ansible
        ```
