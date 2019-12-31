
## Tech Specs

Craft is written in PHP (7+), and built on the [Yii 2 framework](https://www.yiiframework.com/). It can connect to MySQL (5.5+) and PostgreSQL (9.5+) for content storage.

## Install CraftCMS

Requirement:

- [Composer]
- [PHP] version: >=7.1
- [MySQL] version: >=5.6
- [Virtual] [host]
## Set install CraftCMS
- Clone source: git clone https://github.com/nguyendohoangdinh/craftcms.git 
- Run : composer-update
- Run : sudo chmod -R 777 .env composer.json composer.lock config/license.key storage/* vendor/* web/cpresources/*
- Run : ./craft setup/security-key
- Run : ./craft setup
