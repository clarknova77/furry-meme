# Ansible Ad-hoc Commands

` ansible all -m command -a `

+ Runs the command module with the **id** command as its argument against all hosts. Notice that this needs [all] to be defined in the inventory

` ansible all -m command -a id -o`
+ Same command, but with a single line of output.

` ansible all -m command -a env`
+ Fails, as the command module doesn't work through the shell.

***
***

``
