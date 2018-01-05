# dotNetMock
tutorial: https://docs.microsoft.com/en-us/aspnet/core/publishing/iis?tabs=aspnetcore2x

1. install DotNet 2.0: https://www.microsoft.com/net/download/macos
2. cd project folder
3. dotnet restore
4. dotnet build
5. dotnet run
6. create IIS site pointing to publish folder "$windowdir$\netcoreapp2.0\publish" (pool unmanaged) 
7. install .NET Core Windows Server Hosting bundle 2.0 in the iis server
7. dotnet publish: dotnet publish -c release-64 -o C:\Users\syntagma\Documents\test\bin\Debug\netcoreapp2.0\publish --framework netcoreapp2.0
