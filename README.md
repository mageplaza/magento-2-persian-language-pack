## Magento 2 Persian Language Pack

If you are planning to build a store at Iran, and you have a huge difficulty in communication, **Magento 2 Persian Language Pack** is a great suggestion to break that rule. With the Persian Language Package, you are able to be more friendly with the native people in Iran as well as they absolutely feel comfortable at your store. This is a smart way to increase online sales significantly when you want to expand the brand voice in different countries.

Read more [Magento 2 Persian Language Pack](https://www.mageplaza.com/magento-2-persian-language-pack.html)


## Overview

- Download & Contribute
- Install Persian Language Pack
- How to Install Persian Language Pack

## Download & Contribute to Persian Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Persian Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-persian-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-persian-language-pack/tarball/master)
- [Copy & paste package](https://crowdin.com/project/magento-2/fa.zip)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Persian Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method
Install the Persian language pack via composer is never easier.

**Install Persian pack**:

```
composer require mageplaza/magento-2-persian-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy fa-ir

```


**Update  Persian pack**:

```
composer update mageplaza/magento-2-persian-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy fa-ir

```

#### Authentication required (Optional)

[Authentication required](https://i.imgur.com/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### #2. Copy & Paste method

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Persian language pack
- Step 2: Unzip Persian pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Persian language pack

You can download the language pack from above link

#### Step 2: Unzip Persian pack

Unzip the Persian language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually

To download and install Persian pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-persian-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-persian-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `fa_IR.zip` into `app/i18n/mageplaza/fa_IR/fa_IR.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Persian language pack}}](https://i.imgur.com/aPSUA0l.png)


## Translation process of Persian Language Pack
![process](http://progressed.io/bar/80)

Contribute to this language at https://crowdin.com/project/magento-2/fa

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.0.9
- Magento v2.0.10
- Magento v2.0.11
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2
- Magento v2.1.3
- Magento v2.1.4
- Magento v2.1.5



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


References:
- https://www.mageplaza.com/magento-2-persian-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/