# workspace-install



## Getting started

* Install `pip`:

    ```bash
    apt-get -y install python3-pip
    ```

* Install `ansible`:

    ```bash
    python3 -m pip install --upgrade --break-system-packages ansible
    ```

* Create config:
    * Copy example
        ```bash
        cp vars/user.yml.example vars/user.yml
        ```
    * Edit config `vars/user.yml`:

* Run `ansible`:

    ```bash
    ansible-playbook ./playbooks/configure-workstation.yml
    ```
