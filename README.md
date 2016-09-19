
[![Build Status](https://travis-ci.org/AAROC/future-gateway-api-server.svg?branch=master)](https://travis-ci.org/AAROC/future-gateway-api-server) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# future-gateway-api-server

Docker container for the FG API server.

# Building the container

  1. The container should be built using an Ansible playbook
  1. This container uses the [AAROC DevOps repo](https://github.com/AAROC/DevOps), which has the Ansible playbook in it.
  1. The following command should be run to build the container :
        ```bash
           docker build . -f <Dockerfile>
        ```
