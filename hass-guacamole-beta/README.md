## This my first addon for HA, do not plan on extended support.

## Prerequisites

MariaDB is required for this to function. The official "Home Assistant Add-on: MariaDB" should work perfectly with this.

## Installation
1. Add the repository URL under **Supervisor → Add-on Store → ⋮ → Repositories**:

    https://github.com/Kudjo-Grand/ha-addons
2. Find the "Guacamole" add-on and click it.
3. Click on the "INSTALL" button.

note: ingress is currently a work in progress and doesn't work right now. Go to "Configuration" and choose an unused, (preferrably uncommon) port.
You can then reach Guacamole on http://<your HA IP>:<your selected port> (e.g. http://192.168.1.30:8888)
    
## Default User

The default username is `guacadmin` with password `guacadmin`.


## Info

Apache Guacamole for Homeassistant

More info about Guacamole: https://guacamole.apache.org/

based on: https://github.com/MaxWaldorf/guacamole (a fork of: https://github.com/oznu/docker-guacamole )
