
# The test task for the SRE engineer candidates

Create an Ansible role(s) and playbook(s) to bootstrap the sample Django project, use the Ansible-Vault to keep secrets safe.

Check the docker-ce package exists, if not - install the latest docker-ce version for Linux.

## Create docker containers with Django sample app and Postgres
The minimum set of services:
 - app (django)
 - db (postgres)

Run the db container with persistent volume mounted.

Create a container, create DB and user - django.

Run the app container on the optimal base image you choose (explain your choice).

Determine and install all dependencies.

Deploy sample project and run all build tasks.

Put the settings.py template with decrypted secrets to the project's root_dir.
Then, execute app with the uwsgi.

### Be sure to write a detailed description, with usage instructions for end users (it is assumed that this will be the developers).

Source code: https://github.com/kirpit/django-sample-app

Push final project to your GitHub public repository.

#### Optional:
- scaling
- load balancer
- basic monitoring
- demo on [GCE free trial](https://console.cloud.google.com/freetrial) project

Consider how you can extend this task. Any thoughts are welcome.
