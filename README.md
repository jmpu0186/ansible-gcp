# Scripts Ansible Docker Jenkins

_Playbooks para instalación de DOCKER y JENKINS (PLUGINS Y JOBS)_


### Pre-requisitos 📋

_Tener instalado ansible, en mi caso utilizo CENTOS la instalación se hace asi_

```
sudo yum -y install ansible
```

### Ejecucion 🔧

_Para instalar los playbooks ejecutar los comandos_

```
ansible-playbook docker-installation/docker.yml
ansible-playbook jenkins-installation/site.yml
ansible-playbook jenkins-modules/site.yml
```