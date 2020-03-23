config-setup hooks files for SONiC
==================================

Install
-------
```
sudo mkdir -p /etc/config-setup
sudo cp -r config-migration-*-hooks.d /etc/config-setup/
```

Description
-----------
- 00ssh
  Keep ssh host key.

- 01pre-hooks
  Keep config-setup pre hooks.

- 02resolvconf
  Keep /etc/resolv.conf.
