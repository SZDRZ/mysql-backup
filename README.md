# mysql-backup

### Description

This is a backup script for MySQL Database which is using mydumper tools.

### Features

* multi-threads backup support, accelerate your backup speed

* multi-targets support

* backup directory structure

* config file separated from scripts

* upload to cloud object storage support (Aliyun OSS , TencentCloud COS , AWS S3...)

* alerting support (Email , WeXin)

### Features Description

#### - Multi Backup Targets Support

You can use this scripts on a linux machines that is used to backup multiple mysql instances.Don't need to deploy the backup scripts on each database instance.

![](D:\gitproject\github.com\mysql-backup\images\1.drawio.png)

#### 

#### - Backup Directory Structure

![](D:\gitproject\github.com\mysql-backup\images\2.drawio.png)

#### - Config separated from scripts

In my past versions, configuration parameters and scripts were put together.When the script is updated, your previous configuration parameters may be overwritten, and you have to refill the configuration parameters at this time, which is very inconvenient.So, I decided to separate configuration parameters and scripts. This way your configuration parameters will not be overwritten when the script is updated.

![](D:\gitproject\github.com\mysql-backup\images\3.drawio.png)
