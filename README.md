# Ansible

An application was uploaded by Playbook running on two environments:
# Staging and Production

The Staging environment contains weak servers compared to Production's servers.

A connection was made to a master machine between the other machines (VM1 Staging in the Staging environment, and VM1 Production in the Production environment).

The Playbook contains:

Server updates.

Installing Nodejs.

Creating ENV according to data in a separate var file (which was not uploaded here for security reasons but the names of the variables are clear).

Installing the application and connecting to azure database.

Preserving the environment works even after reboot with PM2.
