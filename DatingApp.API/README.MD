dotnet add package Microsoft.EntityFrameworkCore.SqlServer

dotnet add package Microsoft.EntityFrameworkCore  

dotnet add package Microsoft.EntityFrameworkCore.tools 

dotnet add package Microsoft.EntityFrameworkCore.SqlServer  

dotnet add package Microsoft.EntityFrameworkCore.Sqlite

>###### DATABASE

dotnet ef migrations add InitialCreate

dotnet ef migrations add InitialMigration

dotnet ef migrations add AddedUserEntity

dotnet ef database update

dotnet tool install --global dotnet-ef

>npm install -g yo
>npm install -g generator-efrepo
>yo efrepo