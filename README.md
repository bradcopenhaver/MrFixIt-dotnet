### Mr Fix-It
#### A repair technician job service.

The Mr. Fix-It site allows visitors to post jobs that they need someone to help them with. Users can then also register as a "worker" and claim available jobs, then mark them as "in progress" and "completed."

## Setup and Install

#### Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Microsoft Visual Studio](https://www.visualstudio.com/downloads/)
* [Microsoft SQL Server Management Studio (SSMS)](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms#sql-server-management-studio)

#### Installation

Clone this repository and open the solution file `MrFixIt.sln` in Visual Studio. After all package dependencies have loaded,  right click on `MrFixIt` in the `src` folder and select `Build`. When the build is complete, navigate to the same folder in a command terminal and run `dotnet ef database update` to create the database on your local SQL server.

## Known Bugs

None documented right now, but I'm sure there are plenty.

## Possible future version features

* Add better styling overall.
* Add User Roles so that users who only want to post a job don't have to register as a worker.
* Enforce Authorization at the controller level.

## Support and contact details

If you have questions or comments, contact the author at bradcopenhaver@gmail.com

## Technologies Used

* ASP.NET CORE
* C#
* html/css
* Bootstrap

### License

This project is licensed under the MIT license.

Copyright (c) 2017 **Brad Copenhaver**
