FROM quay.io/operator-framework/ansible-operator:v0.6.0

COPY group_vars/ ${HOME}/group_vars/
COPY roles/ ${HOME}/roles/
COPY inventory/ ${HOME}/inventory/
COPY watches.yaml ${HOME}/watches.yaml
COPY playbook.yml ${HOME}/playbook.yml
