# Company_Database

SET NAMES utf8;
SET time_zone = '+00:00';
SET foreign_key_checks = 0;
SET sql_mode = 'NO_AUTO_VALUE_ON_ZERO';

SET NAMES utf8mb4;

DROP TABLE IF EXISTS `products`;
CREATE TABLE `products` (
  `Product_ID` int(36) NOT NULL AUTO_INCREMENT,
  `Product_Name` varchar(30) NOT NULL,
  `Product_Category` varchar(30) NOT NULL,
  `Info` text NOT NULL,
  `Address` varchar(33) NOT NULL,
  `Cost_Expenses` varchar(12) NOT NULL,
  `Order_List` varchar(2888) NOT NULL,
  `Orders_Date` date NOT NULL,
  `Products_Guarantee_Insurance` blob NOT NULL,
  `Product_Fragility_Index` varchar(45) NOT NULL,
  PRIMARY KEY (`Product_ID`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

INSERT INTO `products` (`Product_ID`, `Product_Name`, `Product_Category`, `Info`, `Address`, `Cost_Expenses`, `Order_List`, `Orders_Date`, `Products_Guarantee_Insurance`, `Product_Fragility_Index`) VALUES
(66666666,	'Drums',	'Instruments',	'ssioahdsoadhasodh',	'California Langton Street 8283',	'666€',	'AFHDOFIHDOSFSDGOSFGS',	'0666-06-06',	'1',	'355.583583 PSI'),
(232564224,	'Electric Bass',	'Instruments',	'46810ae1690bb3a0',	'California Langton Street 8283',	'269€',	'AFHDOFIHDOSFSDGOSFGS',	'0666-06-06',	'0',	'355.583583 PSI'),
(235563333,	'Electric Guitar',	'Instruments',	'',	'California Langton Street 8283',	'289€',	'AFHDOFIHDOSFSDGOSFGS',	'0666-06-06',	'0',	'355.583583 PSI'),
(262262646,	'Sitar',	'Instruments',	'gsdgseg',	'California Langton Street 8283',	'119€',	'AFHDOFIHDOSFSDGOSFGS',	'0666-06-06',	'1',	'355.583583 PSI'),
(343253623,	'Pan Flute',	'Instruments',	'asgsgag',	'California Langton Street 8283',	'122€',	'AFHDOFIHDOSFSDGOSFGS',	'0666-06-06',	'1',	'355.583583 PSI'),
(346373477,	'Electric Violin',	'Instruments',	'fassafsa',	'California Langton Street 8283',	'256€',	'AFHDOFIHDOSFSDGOSFGS',	'0666-06-06',	'1',	'355.583583 PSI'),
(346373478,	'Tanpura',	'Instruments',	'fassafsa',	'California Langton Street 8283',	'146€',	'AFHDOFIHDOSFSDGOSFGS',	'0666-06-06',	'1',	'355.583583 PSI'),
(346373481,	'Harpsichord',	'Instruments',	'jfgjfg',	'California Langton Street 8283',	'122€',	'AFHDOFIHDOSFSDGOSFGS',	'0666-06-06',	'0',	'355.583583 PSI'),
(777777777,	'Piano',	'Instruments',	'jzjdzdjdzjfdfj',	'California Langton Street 8283',	'1066€',	'rdfdjfjzjdz',	'0666-06-06',	'0',	'355.583583 PSI'),
(777777778,	'Tablas',	'Instruments',	'fassafsa',	'California Langton Street 8283',	'189$',	'AFHDOFIHDOSFSDGOSFGS',	'0666-06-06',	'0',	'355.583583 PSI');

-- 2020-05-17 04:56:42
