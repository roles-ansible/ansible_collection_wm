[![collection l3d.wm](https://ansible.l3d.space/svg/l3d.wm_ansible-collection_collection.svg)](https://galaxy.ansible.com/ui/repo/published/l3d/wm/)
[![Maintainance](https://ansible.l3d.space/svg/l3d.wm_maintainance_collection.svg)](https://ansible.l3d.space/#l3d.wm)
[![License](https://ansible.l3d.space/svg/l3d.wm_license_collection.svg)](LICENSE)

 Ansible Collection l3d.wm
===============================
Ansible Collection for window manager like i3 and sway

 Ansible Roles:
-----------------
+ l3d.wm.i3
+ l3d.wm.sway


## Using this Collection
You can install the collection using ansible-galaxy by running:
```bash
ansible-galaxy collection install l3d.wm:1.0.4
```

Remember you can to Upgrade to the latest version of the l3d.wm collection using the ``--upgrade`` parameter:
```bash
ansible-galaxy collection install l3d.wm --upgrade
```

Or you could clone this collection in your local ansible project for example to ``collections/ansible_collections/l3d/wm/``.
```
# Clone git Repo to specified path
git clone https://github.com/roles-ansible/ansible_collection_wm.git collections/ansible_collections/l3d/wm/

# change directory
cd collections/ansible_collections/l3d/wm/
```

```yaml
---
collections:
  - name: l3d.wm
    version: ">=1.0.4"
```
