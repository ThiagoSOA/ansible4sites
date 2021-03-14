<h1>Task Ansible for Site PHP, Magento2, Wordpress, Nginx and Tomcat</h1>


This Ansible playbook is for installing Magento 2 Open Source, wordpress, tomcat using nginx reverse proxy, simple website, mysql database (MariaDB)
all on a single server using CentOS 8.

- Ansible 2.9.18
 
Edit file ``hosts``, add the public IP do you server.
Edit the variable file in ``roles/vars/main.yml`` , database name, nginx configuration, package version etc .

After editing the files and vars, you can run the command:

``ansible-playbook -i hosts playbook.yml``

- Directory structure
    
```
.
├── host
├── playbook.yml
└── roles
    ├── banco
    ├── install
    ├── magento
    ├── site
    ├── ssl
    ├── swap
    ├── tomcat
    └── wordpress

9 directories, 2 files
```
# ansible4sites
