# Hair Salon

#### By Curtis Brooks

#### This application saves and displays stylist and client information.

## Technologies Used

* C#
* .NET
* MySQLWorkbench

## Description

This application helps keep track of stylists and clients for a hair salon business. User can input stylist and client information, then view list of all stylists or clients. All clients are assigned to a stylist.

## Setup/Installation Requirements

* Clone [this](https://github.com/curtisbrooks678/HairSalon.Solution) repository to your desktop.
* Set up database, using MySQLWorkbench:
  * Click Administration tab, then Data Import/Restore. 
  * Select Import from Disk, then Import from Self-Contained File.
  * Click ".." to far right of "Import from Self-Contained File" section.
  * Select curtis_brooks.sql from cloned repository folder.
  * Click New button.
  * Enter new Schema name as "curtis_brooks" and click ok.
  * Select "Dump Structure and Data" from drop down.
  * Click Start Import button and the database is set up!
  * To view details on the schema, click the schema tab, then refresh the schema page using the arrows icon just below the schema tab.
* Set up appsettings.json file:
  * In code editor, create "appsettings.json" file in top level of cloned repository directory.
  * Add the following code below to this new file and save: 
    {
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=curtis_brooks;uid=root;pwd=epicodus;"
      }
    }
* To run program:
  * Navigate to the HairSalon directory in your terminal.
  * Type "dotnet run" in your terminal.

## Known Bugs

* No known bugs.

## License

[MIT](https://en.wikipedia.org/wiki/MIT_License) 

Copyright (c) 12/25/21 Curtis Brooks