v0.2-Current
--------
This role now requires python to be installed on the SmartOS hypervisor. This allows much more flexibility and easier module support.

To setup python on your SmartOS hypervisor, set `hypervisor_install_python` to `true`. This can be set in your playbook and will skip if python is already installed.

- Ability to specify `image_name` variable to pull latest image version instead
of needing to use `image_uuid`. `image_uuid` will override `image_name`.
- Preliminary work for getting current virtual machine state.

v0.1
----
First release.
