# Ansible


# Directory Structure:

![image](https://github.com/KarthiCholan/Ansible/assets/108706606/12a11b63-fb90-49a6-825d-484f6f1bb00c)





The playbook deploy_prometheus_grafana.yml includes two roles, prometheus and grafana.
The prometheus role installs Prometheus and copies a template configuration file (prometheus.yml.j2).
The grafana role adds the Grafana APT repository, installs Grafana, and starts the Grafana service.


# ansible-playbook -i deploy_prometheus_grafana/inventory.ini deploy_prometheus_grafana.yml




