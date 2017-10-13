# Ansible-Work
Ansible work

In order to use this script, you must point the inventory.txt to a computer that is set up for ansible.
Two variables must also be created in order for this script to pull files off of github.
  - githubuser
  - githubpassword
  
You can include this at the top of the db_and_flask_app.yml file or pass the vars from another file.

an example command to run this is:
$ ansible-playbook db_and_flask_app.yml -i inventory.txt --ask-sudo-pass
