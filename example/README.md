Populate inventory file and then
```bash
ansible-galaxy install -r requirements.yml --force
ansible-playbook -i example_inventory.yml playbook.yml
```
