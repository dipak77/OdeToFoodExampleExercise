Create the database
The following steps use migrations to create a database.

Run the following commands in Package Manager Console (PMC)
Install-Package Microsoft.EntityFrameworkCore.Tools
Add-Migration InitialCreate
Update-Database
