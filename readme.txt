Manage Odoo Docker stack, module upgrade, backup, and reset with one script.

How to Install on Linux Machine

Steps:
1. Clone this repository:
	git clone https://github.com/bydzen/odoo.git
2. Enter the directory:
	cd odoo/
3. Copy main file to binary:
	sudo cp odoo /usr/bin/
4. Make executable:
	sudo chmod +x /usr/bin/odoo

Usage:
odoo [command]

Commands:
  up                       Start containers in background
  down                     Stop and remove containers
  stop                     Stop containers
  restart                  Restart Odoo web container
  logs                     Show Odoo web logs (follow)
  ps                       Show container status
  build                    Rebuild containers
  shell                    Open Odoo shell
  update <module|all>      Upgrade module(s) and restart web
  upgrade <module|all>     Same as update
  backup                   Backup data/ directory and filestore
  reset --yes              Backup then wipe data/ directory

Optional:
  ODOO_DB=<db_name> odoo shell
  ODOO_DB=<db_name> odoo upgrade <module|all>

Help:
odoo

Enjoy.
