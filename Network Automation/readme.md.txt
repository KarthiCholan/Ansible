Encrypt the vault file:

bash
Copy code
ansible-vault encrypt vault_switch_creds.yml
Replace "your_switch_username", "your_switch_password", and other placeholder values with your actual network switch credentials and configuration.

Run the playbook:

bash
Copy code
ansible-playbook -i inventory.ini --ask-vault-pass network_automation.yml
Replace network_switches with the group of network switches you want to configure in your inventory file. Adjust the tasks and variables based on your specific network infrastructure and automation requirements.





