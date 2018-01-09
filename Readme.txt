Example from: 
https://www.journaldev.com/2603/spring-transaction-management-jdbc-example#spring-transaction-management-jdbc-example
By Pankaj on JULY 29, 2017
Retrieved on 01/08/2018


Create connection 
DBTest

Create on schema:

CREATE TABLE `Customer` (
  `id` int(11) unsigned NOT NULL,
  `name` varchar(20) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;
CREATE TABLE `Address` (
  `id` int(11) unsigned NOT NULL,
  `address` varchar(20) DEFAULT NULL,
  `country` varchar(20) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;