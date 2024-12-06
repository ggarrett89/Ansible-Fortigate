# Ansible-Fortigate

This Repo is an example of how to create IP addresses, Firewall policies and Custom services on any fortigate. Using Ansible playbook to create, change or delete one of these resources

# Requirements
a running Fortigate >=6.0.0 ansible>=2.15.0 fortinet.fortios ansible collection create a access API token in Fortigate GUI variables in ansible playbook or inventory to access httpapi ansible_connection: httpapi ansible_httpapi_use_ssl: True ansible_httpapi_validate_certs: False ansible_network_os

