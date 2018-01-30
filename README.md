# main-tso-playbook

This is designed for Ansible-Tower to run. If you want to run on ansible-playbook, you should remove the variable like this {{ user }} and put your own variable or add your variable on group_vars/all (sorry it's encrypted by vault).  This is using Ansible-Tower surveys to get the variable/s and integrate with playbook.  Some of the files are encrypted too with ansible-vault like group_vars/all, but all is global variable definition.  Some script is also encrypted.  

Created by Venerari and Lazaroall.
