TerraformSetup
=========

Ansible role to automate the setup of terraform


Role Variables
--------------

- golang_url: GoLang download url for Red Hat systems
- terraform_url: Terraform download url for Red Hat systems


Example Playbook
----------------
    - hosts: terraform_hosts
      roles:
         - { role: hosninabil.terraformsetup }

License
-------

Apache-2.0

Author Information
------------------
Nabil Hosni, cloud engineer and opensource enthusiast.
