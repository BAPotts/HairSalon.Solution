# _HairSalon_

#### _C# Exercise for Epicodus, 07/31/20_

#### By _**Beverly Potts**_

## Description

_A website to track the clients and stylists of Eau Claire Hair Salon.It allows the user to maintain and edit a list of stylists and their associated clients._

## Specifications

| Behavior   |   Input   |  Output |
|----------|:-------------:|------:|
|Webpage will display a list of all stylists|n/a|n/a|
|Webpage will display details and client list of a selected stylist|n/a|n/a|
|Webpage will allow new stylists to be added|n/a|n/a|
|Webpage will allow new clients to be added to a specific stylist|||
|Webpage will not allow clients if there are no existing stylists|||



## Setup/Installation Requirements


  1. Follow this [link to the project repository](https://github.com/BAPotts/HairSalon.Solution.git) on GitHub. 
  2. Click on the "Clone or download" button to copy the project link.     
  3. If you are comfortable with the command line, you can copy the project link and clone it through your command line with the command `git clone`. Otherwise, I recommend choosing "**Download ZIP**".     
   4. Once the ZIP file has finished downloading, you can right click on the file to view the zip folder in your downloads.     
  5. Right click on the project ZIP folder that you have just downloaded and choose the option "**Copy To...**", then choose the location where you would like to save this folder.      
  6. Navigate to the final location where you have chosen to save the project folder.      
  7. To view the code itself, right click, choose "open with..." and open using a text editor such as VS Code or Atom, etc.
  8. Open the terminal inside of your text editor.
  9. From inside of the HairSalon directory, type the command `dotnet restore` into your terminal and hit enter. You should see object files appear. They should be greyed out.

DROP DATABASE IF EXISTS `Beverly_Potts`;
CREATE DATABASE `Beverly_Potts`;

USE `Beverly_Potts`;

CREATE TABLE `Clients` (
  `ClientId` int NOT NULL AUTO_INCREMENT,
  `Name` varchar(255) DEFAULT NULL,
  `StylistId` int DEFAULT '0',
  PRIMARY KEY (`ClientId`)
) ENGINE=InnoDB AUTO_INCREMENT=10 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;


CREATE TABLE `Stylists` (
  `StylistId` int NOT NULL AUTO_INCREMENT,
  `Name` varchar(255) NOT NULL,
  PRIMARY KEY (`StylistId`)
) ENGINE=InnoDB AUTO_INCREMENT=10 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;





## Known Bugs

There are no known bugs at this time.

## Support and contact details

Feedback is greatly appreciated! Contact BAPotts on GitHub with any questions or comments.

## Technologies Used

* C# 
* .NET-Core 2.2
* Visual Studio Code
* Git Version Control 
* GitHub
* Sql Workbench 8.0

### License

*This project is licensed under the MIT license.*

Copyright (c) 2020 **_{Beverly Potts}_**