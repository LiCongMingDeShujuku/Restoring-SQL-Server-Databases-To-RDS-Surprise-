![CLEVER DATA GIT REPO](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/0-clever-data-github.png "李聪明的数据库")

# 将SQL Server数据库还原到RDS？
#### Restoring SQL Server Databases To RDS? Surprise!

## Contents

- [中文](#中文)
- [English](#English)
- [Build Info](#Build-Info)
- [Author](#Author)
- [License](#License) 


## 中文
如果你从Amazon RDS SQL实例开始使用Amazon RDS，那么你会发现它是一个出色的解决方案。换句话说，安装应用程序，并将它们指向你的RDS实例，以便它可以创建它的数据库。如果你正在开发自定义数据库解决方案，并开始直接在Amazon RDS中构建数据库，那你也应该没问题。然而，在从任何以前的非RDS SQL数据库环境导入/恢复数据库或数据集时，你会发现任务极其复杂。它具有严格的限制，超出了所有行业导入/迁移规范。另外，在源数据库环境中创建的任何自动数据库进程，或整个企业中的任何复制方案都不受支持。我对未来充满信心，Amazon RDS将发展该产品，包括对各种导入和恢复操作的广泛支持，包括数据库自动化。然而现在情况并非如此。这令我感到意外。

数据库迁移是可能的，但它需要是一个完整的自定义“手动”解决方案，你可以通过该解决方案单独定位每个数据库，表和后续对象。这是完整的ETL开发。这需要编写SQL逻辑，并且很可能通过Integration Services（SSIS）管理ETL过程。请记得，这是每个数据库，每个对象都需要完成的。一旦模式和数据被正确移动，就需要在目的地重新创建一些对象。

## English
Amazon RDS is an excellent solution if you are starting with an Amazon RDS SQL Instance, and you’re immediately using it directly. In other words installing applications, and pointing them to your RDS instance so it can create it’s databases. If you are developing custom database solutions, and start building out databases directly in Amazon RDS; then you should also be fine. However; you will find the task extremely complicated when importing/restoring databases, or data sets from any former non-RDS SQL database environments. It has severe limitations that are outside all industry import/migration norms. Additionally; any automated database processes that were created on the source database environments, or any replication schemes across the enterprise will not be support. I’m confident in the future; Amazon RDS will evolve this product to include wide scale support of all kinds of import & restore operations including database automations however; right now this is not the case. This caught me by surprise.

Database migrations are possible, but it needs to be a complete custom ‘manual’ solution by which you would target each and every database, table, and subsequent objects individually. This is full ETL development for ETL. SQL logic will need to be written and the ETL process will most likely be managed via Integration Services (SSIS). Remember; this is done per database, per object. Once the schema, and data have been properly moved some objects will need to be recreated at the destination.

![#](images/Restoring-SQL-Server-Databases-To-RDS-Surprise-01.png?raw=true "#")

See the Amazon Docs directly here: 

点击此链接查看Amazon Docs：
http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/SQLServer.Procedural.Importing.html


[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

- **李聪明的数据库 Lee's Clever Data**
- **Mike的数据库宝典 Mikes Database Collection**
- **李聪明的数据库** "Lee Songming"

[![Gist](https://img.shields.io/badge/Gist-李聪明的数据库-<COLOR>.svg)](https://gist.github.com/congmingshuju)
[![Twitter](https://img.shields.io/badge/Twitter-mike的数据库宝典-<COLOR>.svg)](https://twitter.com/mikesdatawork?lang=en)
[![Wordpress](https://img.shields.io/badge/Wordpress-mike的数据库宝典-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)

---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Lee Songming](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/1-clever-data-github.png "李聪明的数据库")

