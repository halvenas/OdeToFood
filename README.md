# OdeToFood
repository for project from plurlasight course asp.net core fundamentals


dotnet tool install --global dotnet-ef -v 2.1.4

dotnet-ef migrations add initialcreate -s ..\OdeToFood\OdeToFood.csproj

dotnet ef database update -s ..\OdeToFood\OdeToFood.csproj
