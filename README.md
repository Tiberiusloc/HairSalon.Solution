# Eau Claire's Hair Salon

#### Tiberius Lockett

## Description

Eau Claire's Hair Salon is an application allowing a salon owner to create, edit, and store a list of clients organized by which stylist they belong to. 


## Logistics

|                    | Minimum Product Features |
| ------------------ | ------------------------ |
| :heavy_check_mark: | Do the database table and column names follow proper naming conventions?                         |
| :heavy_check_mark: | Do the project folder and exported database follow the specific naming requirements for this project?                         |
| :heavy_check_mark: | Are the instructions for re-creating your database thorough and clear?                         |
| :heavy_check_mark: | Is there a one-to-many relationship set up correctly in the database?                         |
| :heavy_check_mark: | Is CREATE functionality included for one class and is CREATE and VIEW functionality included for the other class?                         |
| :heavy_check_mark: | Build files and sensitive information are included in .gitignore file and is not to be tracked by Git, and includes instructions on how to create the appsettings.json and set up the project.                         |
| :heavy_check_mark: | Project is in a polished, portfolio-quality state.                         |
| :heavy_check_mark: | The prompt’s required functionality and baseline project requirements are in place by the deadline.                         |

## Setup/Installation Requirements

1. Clone this projects repository into your local directory following [these](https://www.linode.com/docs/development/version-control/how-to-install-git-and-clone-a-github-repository/) instructions.

2. Navigate to project directory from your terminal by entering the following:

```
cd HairSalon.Solution
```

3. Download [.NET Core](https://docs.microsoft.com/en-us/dotnet/core/install/windows?pivots=os-windows&tabs=net60)

4.  Install:
`dotnet tool install -g`

5. Navigate to `HairSalon` directory and run `$ dotnet run build` in your terminal.

6. Within the same project folder enter `dotnet watch run` to open a live server.

8. Go to your browser and enter the url:
`http.://localhost:5000`

### MySQL Install and Configuration:
* Windows Installation:

1. Start by downloading the MySQL Web Installer from the [MySQL Downloads](https://dev.mysql.com/downloads/installer/) page. This will allow you to install both the MySQL Community Server and the MySQL Workbench.
2. On the configuration page of the installer select the following options:
* Use legacy password encryption
* Set your password
3. Open the terminal and enter the command: *'export PATH="/usr/local/mysql/bin:$PATH"' >> ~/.bash_profile
4. Download the MySQL Workbench DMG file [here](https://dev.mysql.com/downloads/file/?id=484391) if you haven't already.
5. Open Local Instance 3306 with the password you set.
6. Import database file from project directory `tiberius_lockett.sql` in MySQL Workbench to import database for you to recreate.

*  Create `appsettings.json` file in top of project directory and copy in the following, with the password:
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=tiberius_lockett;uid=root;pwd=[YOUR_PASSWORD_HERE];"
  }
}

## Technologies Used

* C#
* .NET Core
* Entity
* MySQL Workbench




## Known Bugs

* Any known issues


## License
[GNU GPL3.0](https://choosealicense.com/licenses/gpl-3.0/)

## Contact Information
Tiberius Lockett <tlockett680@gmail.com>

Copyright (c) _10/2022_ _Tiberius Lockett_