# How to get started

### Check System Requirements
https://experienceleague.adobe.com/docs/commerce-operations/installation-guide/system-requirements.html
<br/>
<br/>
PS: Check project version running: `bin/magento --version` 

### Create empty database

`mysql> CREATE DATABASE test;`

### Composer
`composer install`

### Initiate elasticsearch/opensearch
`evm start`

### Setup the project
`php bin/magento setup:install --base-url="http://dev.test" --db-host="localhost" --db-name="test" --db-user="root" --db-password="test123" --admin-firstname="admin" --admin-lastname="lastname" --admin-email="user@example.com" --admin-user="admin" --admin-password="admin123" --language="en_US" --currency="EUR" --timezone="Europe/Lisbon" --use-rewrites="1" --backend-frontname="admin"`
