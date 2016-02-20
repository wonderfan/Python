### window installation

try this practise in future

### Install on C9 by source codes

1. clone the codes or download the source codes
  - https://github.com/odoo/odoo.git
  - https://nightly.odoo.com/9.0/nightly/src/odoo_9.0.latest.zip
  
2. use the postgresql guide: 
  - https://community.c9.io/t/setting-up-postgresql/1573
  - http://www.postgresql.org/docs/9.1/static/sql-commands.html
  - http://www.postgresql.org/docs/9.4/static/app-psql.html

3. create postgrel user and role: 

  ```
  sudo su - postgres -c "createuser -s $USER"
  
  sudo sudo -u postgres psql
  postgres=# CREATE USER "ubuntu"
  ```

4. install the dependencies:

  ```
   pip install -r requirements.txt
  ```

5. install css less tools
