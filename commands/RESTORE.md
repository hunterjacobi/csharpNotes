# DotNet Restore

The dotnet restore command uses NuGet to restore dependencies as well as project-specific tools that are specified in the project file. In most cases, you don't need to explicitly use the dotnet restore command, since a NuGet restore is run implicitly if necessary when you run the following commands:

1. dotnet new
2. dotnet build
3. dotnet build-server
4. dotnet run
5. dotnet test
6. dotnet publish
7. dotnet pack

Sometimes, it might be inconvenient to run the implicit NuGet restore with these commands. For example, some automated systems, such as build systems, need to call dotnet restore explicitly to control when the restore occurs so that they can control network usage. To prevent the implicit NuGet restore, you can use the --no-restore flag with any of these commands to disable implicit restore.

## Calling on the restore command

To call on the add command you use "dotnet restore".

## Resources

- [.Net Restore Documentaion](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-restore)

---

[Back To Home](../readme.md)
