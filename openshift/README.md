# Run playbook

ansible-playbook -i hosts openshift-playbooks/create_user.yaml  --extra-vars "@test.json"
