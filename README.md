# PaymentRegiterAPI
PaymentRecordApp
This project is an asp.net core web api applicationwith angular 11using entity framework core and sql server.

Prerequirement
Visual Studio 2017
NET Core SDK
SQL Server
Visual Studio Code
How To Run
Run on Visual Studio
Install Visual Studio 2019 for your platform if didn't install yet.
Install Visual Studio 2019 Tools if didn't install yet.
Clone or download this repository to local machine.
Open project
Create dbsettings.json - see more below
Debug -> Start debugging


Create dbsettings.json
Create file dbsettings.json to point the ms sql server on your local machine
{
  "ConnectionStrings": {
    "DefaultConnection": "User ID=your-user;Password=your-password;Host=your-host;Port=5432;Database=your-db-name;Pooling=true;"
  }
}

Run on Visual studio Code
Download the angular project
