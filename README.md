# HOW to EXECUTE WLST SCRIPTS via ANSIBLE PLAYBOOKS

This project serves as an example of executing scripts prepared for the WebLogic Scripting Tool across multiple servers via Ansible. In cases where not all servers have the same WebLogic environment variables set, the required environment variables are retrieved from a running WebLogic process on the server to avoid errors. Consequently, the playbook template provided in this project enables the execution of any desired WLST script through Ansible.
