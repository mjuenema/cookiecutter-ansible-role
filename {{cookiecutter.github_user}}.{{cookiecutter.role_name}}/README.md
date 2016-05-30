# {{cookiecutter.role_name}}

{{cookiecutter.short_description}}

## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Example

First install the role into your Ansible configuration.

    cd roles/
    ansible-galaxy install {{cookiecutter.github_user}}.{{cookiecutter.role_name}}
    
Alternatively one can clone the Github repository directly.

    cd roles/
    git clone https::/github.com/{{cookiecutter.github_user}}/ansible-role-{{cookiecutter.role_name}}.git {{cookiecutter.github_user}}.{{cookiecutter.role_name}}
    cd {{cookiecutter.github_user}}.{{cookiecutter.role_name}}
    git checkout ...

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: {{cookiecutter.github_user}}.{{cookiecutter.role_name}} }

## Testing

The ```tests/``` directory contains a simple playbook for testing this role.

    ansible-playbook --check -i {{cookiecutter.github_user}}.{{cookiecutter.role_name}}/tests/inventory {{cookiecutter.github_user}}.{{cookiecutter.role_name}}/tests/test.yml

## Status

Planning

## License

BSD

## Author Information

{{cookiecutter.full_name}} 
{{cookiecutter.email}}
