# Magento 2.3.4 Docker Image and MagePack 2.3.2 

# Setup
Edit the bin/setup variables:
--db-host=db \
  --db-name= \
  --db-user= \
  --db-password= \
  --base-url=https://$BASE_URL/ \
  --admin-firstname= \
  --admin-lastname= \
  --admin-email= \
  --admin-user=rafael \
  --admin-password= \
  
Rename the db.env.sample to db.env and assign value to the variables

MYSQL_ROOT_PASSWORD=

MYSQL_DATABASE=

MYSQL_USER=

MYSQL_PASSWORD=

  
Run bin/setup develomagepack.test or any base url of your choice
