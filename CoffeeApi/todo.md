### Create new App
dotnet new webapi -o TodoApi
cd TodoApi
dotnet add package Microsoft.EntityFrameworkCore.InMemory --prerelease
code -r ../TodoApi

### Run test
dotnet dev-certs https --trust


### Run local webserver
dotnet run