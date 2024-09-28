![](https://github.com/is-leeroy-jenkins/Cammy/blob/main/Resources/Assets/GitHubImages/Cammy.png)

## Cammie is a tool that displays a webcam feed in a WPF Application. Cammie can also be used to directly scan a QR Code when displayed in front of the camera. Cammis is written in C# and released under the MIT license.

####

## ![](https://github.com/is-leeroy-jenkins/Cammy/blob/main/Resources/Assets/GitHubImages/features.png) Features

- Mutliple data providers.
- Charting and reporting.
- Internal web browser, [Baby](https://github.com/is-leeroy-jenkins/Baby/blob/main/README.md),  with queries optimized for searching .gov domains.
- Pre-defined schema for moret than 100 environmental data models.
- Editors for SQLite, SQL Compact Edition, MS Access, SQL Server Express.
- Excel-ish UI on top of a real databases.
- Mapping for congressional earmark reporting and montioring of polluction sites.
- Finanical data bound to environmental programs and statutory authority.
- Ad-hoc calculations.
- Add agency/region/division-specific branding.
- The winforms version of Cammy is [Sherpa](https://github.com/is-leeroy-jenkins/Sherpa?tab=readme-ov-file) 

## ![](https://github.com/is-leeroy-jenkins/Cammy/blob/main/Resources/Assets/GitHubImages/Providers.png) Providers

- [SQLite](https://sqlite.org/index.html) is a C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine. 
- [SQL CE](https://www.microsoft.com/en-us/download/details.aspx?id=30709) is a discontinued but still useful relational database produced by Microsoft for applications that run on mobile devices and desktops. 
- [SQL Server Express Edition](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) is a scaled down, free edition of SQL Server, which includes the core database engine.
- MS Access is a database management system (DBMS) from Microsoft that combines the relational Access Database Engine (ACE) with a graphical user interface and software-development tools. [more here](https://www.microsoft.com/en-us/microsoft-365/access)


## ![](https://github.com/is-leeroy-jenkins/Cammy/blob/main/Resources/Assets/GitHubImages/system_requirements.png) System requirements

- You need [VC++ 2019 Runtime](https://aka.ms/vs/17/release/vc_redist.x64.exe) 32-bit and 64-bit versions

- You will need .NET 8.

- You will need to install the version of VC++ Runtime 



## ![](https://github.com/is-leeroy-jenkins/Cammy/blob/main/Resources/Assets/GitHubImages/documentation.png) Documentation

- [User Guide](Resources/Github/Users.md)
- [Compilation Guide](Resources/Github/Compilation.md)
- [Configuration Guide](Resources/Github/Configuration.md)
- [Distribution Guide](Resources/Github/Distribution.md)


## ![](https://github.com/is-leeroy-jenkins/Cammy/blob/main/Resources/Assets/GitHubImages/csharp.png) Code

- Cammy uses CefSharp 106 for Baby Browser and is built on NET 6
- Cammy supports AnyCPU as well as x86/x64 specific builds
- [Controls](https://github.com/is-leeroy-jenkins/Cammy/tree/main/Controls) - main UI layer and associated controls and related functionality.
- [Enumerations](https://github.com/is-leeroy-jenkins/Cammy/tree/main/Enumerations) - various enumerations used for budgetary accounting.
- [Extensions](https://github.com/is-leeroy-jenkins/Cammy/tree/main/Extensions)- useful extension methods for budget analysis by type.
- [Clients](https://github.com/is-leeroy-jenkins/Cammy/tree/main/Clients) - other tools used and available.
- [Ninja](https://github.com/is-leeroy-jenkins/Cammy/tree/main/Ninja) - models used in EPA budget data analysis.
- [IO](https://github.com/is-leeroy-jenkins/Cammy/tree/main/IO) - input output classes used for networking and the file systemm.
- [Static](https://github.com/is-leeroy-jenkins/Cammy/tree/main/Static) - static types used in the analysis of environmental budget data.
- [Interfaces](https://github.com/is-leeroy-jenkins/Cammy/tree/Interfaces) - abstractions used in the analysis of environmental budget data.
- `bin` - Binaries are included in the `bin` folder due to the complex Baby setup required. Don't empty this folder.
- `bin/storage` - HTML and JS required for downloads manager and custom error pages

## ![](https://github.com/is-leeroy-jenkins/Cammy/blob/main/Resources/Assets/GitHubImages/tools.png)  Data Tools
- ##### Datagrids
- ##### Pivot Tables
- ##### Plotting






