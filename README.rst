cookiecutter-ansible-role
=========================

Cookiecutter_ template for creating Ansible_ roles.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _Ansible: http://www.ansible.com

Usage:

.. code-block:: console

   $ cookiecutter https://github.com/mjuenema/cookiecutter-ansible-role.git
   full_name [Markus Juenemann]: John Smith
   email [markus@juenemann.net]: john.smith@example.com
   github_user [mjuenema]: smith
   role_name [ROLENAME]: example
   short_description [DESCRIPTION]: An example role

   $ ls smith.example/
   defaults  files  handlers  meta  README.md  tasks  templates  tests  vars
