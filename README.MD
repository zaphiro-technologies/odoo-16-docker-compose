# Odoo set-up

This repository allows to start-up a docker stack aligned with Zaphiro online
cluster configuration.

To start it:

1. Create a backup from the production database (before it may be a good idea to
   disable email, to avoid spam during dev tests).
1. Clone the addons project (https://github.com/zaphiro-technologies/odoo-addons)
1. Start the docker stack `docker compose up -d`
1. Restored the `zaphiro` backup from the production database.
1. Change the database to `zaphiro`.
