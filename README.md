Ansible playbook for ELK installation on Jessie.
================================================


1. Prerequisites :
  * This playbook will mostly probably work on **Debian Jessie** only.
  * Ansible version >= 2.3.0
  * Edit *host* file to match yours.
  * Be sure to create your ELK user and that it can sudo without password.
  * In main.yml, edit *host:* to match the host you declared in your host file.

2. Usage :
+ First time installation :

```
        chmod +x run
	./run

```

+ If in need to rerun playbook without packages installation :
```
        ./run --extra-vars "skip_install=true"

```
