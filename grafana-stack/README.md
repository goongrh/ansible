# Here is an ansible-playbook to install Grafana Stack

  **Grafana, Prometheus, Node Exporter, and Blackbox Exporter**

## Environment

  - **CentOs 7**


### How to use?

1. Edit hosts file by adding IP Address of the server to be executed
2. Run following command
   ```
   ansible-playbook -i hosts <file.yml> --ask-become-pass
   ```
