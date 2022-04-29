# workstation-playbook

Playbook for Pop!_OS

## Requirements

Start off by installing Ansible on the system.

For Debian based distros:

```
sudo apt install python3-pip
pip install --user ansible
```

## Usage

- Clone the git repo
```
git clone git@github.com:dylf/workstation-playbook.git
```

- Install the dependencies via ansible-galaxy
```
ansible-galaxy install -r requirements.yml
```