# add-sudoers

### variables
`sudoers_cfg_file:` /etc/sudoers

`sudoers_dropin_dir:` /etc/sudoers.d

```yaml
sudoers_groups:
  - aix_admins # list of groups to add
  - linux_admins
```
`sudoers_file:` "ansible-sudoers" # name of drop in file
