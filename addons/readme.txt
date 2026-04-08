This folder is used to store custom Odoo modules/addons.
All addon folders placed here will be mounted to '/mnt/extra-addons' inside the Odoo container.

How to use custom addons:
1. Extract or clone your Odoo module into this folder.
2. Restart the Odoo container (using `./odoo restart` or `docker compose restart web`).
3. Log in to Odoo with Developer Mode enabled.
4. Go to the Apps menu -> Update Apps List.
5. Search for your module and click Install.
