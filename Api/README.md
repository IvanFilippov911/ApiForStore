### 001 init project

```bash
dotnet new sln -n StoreApi
dotnet new webapi -n Api
dotnet sln add ./Api/Api.csproj
dotnet new gitignore
cd Api
dotnet watch --no-hot-reload
```

### 002 Installing libraries

```bash
dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer
dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.Tools
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Npgsql.EntityFrameworkCore.PostgreSQL
dotnet add package Microsoft.AspNetCore.OpenApi
dotnet add package Bogus
	```