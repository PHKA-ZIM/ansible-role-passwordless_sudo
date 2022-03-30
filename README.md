# Passwordless sudo automation with ansible

## Installation steps

- Go to you ansible project folder
- Add following to your requirements file

```
- src: https://github.com/PHKA-ZIM/ansible-role-passwordless_sudo
  name: ansible-role-passwordless_sudo
```

- Install to project roles path
```
ansible-galaxy install -r requirements.yml --roles-path ./roles
```

## Use ansible-role-ansible-role-passwordless_sudo

- Import role and override role variables, e.g.
```
- name: Enable passwordless sudo
  roles:
    - role: ansible-role-passwordless_sudo
```
