# ansible-dynamic-inventory-scripts
If using the mysql dynamic inventory script as a custom script in Ansible Tower, you need to install the mysql-connector plugins to the ansible virtual env
```source /var/lib/awx/venv/ansible/bin/activate
   pip install mysql-connector mysql-connector-python mysql-connector-python-rf
```
