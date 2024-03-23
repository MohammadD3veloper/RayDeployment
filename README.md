# RayDeployment

Simple ansible playbook to install requirements and configurations on server
then bringing up 3xui by docker-compose up


## Usage

### Create log and inventory directory

add your servers / server on files on it

> directory architecture:

    - log/
        - ansible.log # no matter if you didnt create
    - inventory/
        - server.yml
        - server2.yml
        - etc...
    - playbook/
        ...
### run project

Just run the playbook and answer the prompts then take a coffee till its getting completed.

$ ``` ansible-playbook -i inventory playbooks/main.yml ```

## Contribute
i'll be glad if you want to contribute and adding features to this repository.

just make a pull request and ill merge it :D
