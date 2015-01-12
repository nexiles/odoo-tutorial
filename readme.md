## ODOO Tutorial

### Abstract

This repo is a detup for doing the odoo tutorial.

### Setup

#. clone this repo
#. Do a `git submodule init`
#. Do a `git submodule update`
#. Clone odoo from the nexiles repo to `~/develp/nexiles/odoo`
# Add `192.168.33.2 odoo-dev.nexiles.local` to your `/etc/hosts`
#. Do a `vagrant up`

### Odoo First run

Go to:  http://odoo-dev.nexiles.local

On the first startup of odoo, no database is available.  You
are presented with a dp creation tool.  Please enter:

- "development" as database name
- "12345" as password

### Odoo URLs

Odoo database Manager.  This is where you manage (create, delete, backup, ...)
Odoo database instances:

http://odoo-dev.nexiles.local/web/database/manager#action=database_manager

Odoo Web Interface:

http://odoo-dev.nexiles.local/web

### Resources

Odoo Docs:

https://www.odoo.com/documentation/8.0/

Older, still relevant:

http://de.slideshare.net/openobject/how-to-customize-views-menues-of-open-erp-online-in-a-sustainable-way-frederic-gilson
http://de.slideshare.net/arcanetdeveloper/openerp-book-versin-61?next_slideshow=1
