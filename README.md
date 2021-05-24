# ansible-role-nfs

An Ansible Role installs and configures NFS on Linux systems.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see defaults/main.yml):

```yml
nfs_exports: ["/home/public *(rw,sync,no_root_squash)"]
```

Set exported directories

## Dependencies

None.
