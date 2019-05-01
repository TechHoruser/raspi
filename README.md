## Generación máquina virtual (centos7) con vagrant
Ejecutar:
```
cd vm
vagrant up
```

## Instalar Jenkins con Ansible en vm
Ejecutar el comando:
```
ansible-playbook -i ansible/hosts.yml ansible/jenkins.yml
```
