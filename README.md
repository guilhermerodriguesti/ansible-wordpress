# Ansible-Wordpress
## Architecture 

![Image](./assets/img/Arquitetura.png)

## Roles

* Webserver
* Wordpress
* MySQL

# Run Playbook:

```
ansible-playbook -i hosts provisioning.yml
```

# Tests

```
$ ansible -u vagrant --private-key .vagrant/machines/wordpress/virtualbox/private_key -i hosts -m shell -a 'echo Hello, World'
```


