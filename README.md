## ansible-docker-debian12
Ansible playbook for installation of docker to debian 12

### Why
Geerlingguy role didn't work in the moment of need, so I had to improvise.

## How to
### Set python virtual environment 
```bash
python -m venv .venv
source .venv/bin/activate
pip install ansible
deactivate
```
### Run playbook
```bash
source .venv/bin/activate
ansible-playbook -i inventory.yml docker-debian12.yml
```
