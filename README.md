# Ansible-Examples
How Ansible Works?
There are many similar automation tools available like Puppet, Capistrano, Chef, Salt, Space Walk etc, but Ansible categorize into two types of server: controlling machines and nodes.

The controlling machine, where Ansible is installed and Nodes are managed by this controlling machine over SSH. The location of nodes are specified by controlling machine through its inventory.

The controlling machine (Ansible) deploys modules to nodes using SSH protocol and these modules are stored temporarily on remote nodes and communicate with the Ansible machine through a JSON connection over the standard output.


Prerequisites
Operating System: RHEL/CentOS/Fedora and Ubuntu/Debian/Linux Mint
Jinja2: A modern, fast and easy to use stand-alone template engine for Python.
PyYAML: A YAML parser and emitter for the Python programming language.
parmiko: A native Python SSHv2 channel library.
httplib2: A comprehensive HTTP client library.
sshpass: A non-interactive ssh password authentication.

