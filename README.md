Ansible playbook permettant de déployer un wordpress sur deux machines.

Editer les fichiers .yml dans host_var selon l'ip/username de vos machines.

Lancer le plays site.yml puis wordpress.yml avec ces commandes à la racine :   
                                                    - ansible-playbook plays/site.yml  
                                                    - ansible-playbook plays/wordpress.yml  
# ansible
