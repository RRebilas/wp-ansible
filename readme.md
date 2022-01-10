#### Ansible automatic installation

### Run script command
  ``ansible-playbook -i ``

### Configuration
## 0. Add studentkey to ssh agent
## 1. Set machine ip in hosts.ini
## 2. Setup wordpress in setup_wp.yaml
 - Install httpd server
 - Copy apache cnfg file into etc
 - Download, extract and copy WP archive into ``/var/www``
 - Install epel and remi repo
 - Install php packages
 - Add MariaDB repo cfg to yum conf
 - Install MariaDB server packages
 - Start db server
 - Create db, create user and grand privileges
 - Create wp-config and put it in wordpress catalog
 - Restart Apache
## 3. Run script command from above