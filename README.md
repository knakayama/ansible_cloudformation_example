How to Use
==========

```bash
$ ssh-keygen -f roles/build/file/keys/site_key -N ''
# build
$ ansible-playbook site.yml -vv --tags build
# destroy
$ ansible-playbook site.yml -vv --tags destroy
```
