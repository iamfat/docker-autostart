docker-autostart
================

Upstart script to autostart and maintain docker containers

## How to use it?
1. make sure that you've already installed docker
2. put `docker-autostart.conf` and `docker-start.conf` to `/etc/init`
3. add following line to `/etc/default/docker`

    ```bash
    AUTOSTART_CONTAINERS="<container1> <container2> <container3>"
    ```
4. done.