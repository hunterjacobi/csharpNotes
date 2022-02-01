# dotnet publish

Publishes the application and its dependencies to a folder for deployment to a hosting system.

```
dotnet publish
```

## Description

dotnet publish compiles the application, reads through its dependencies specified in the project file, and publishes the resulting set of files to a directory. The output includes the following assets:

Intermediate Language (IL) code in an assembly with a dll extension.

A .deps.json file that includes all of the dependencies of the project.

A .runtimeconfig.json file that specifies the shared runtime that the application expects, as well as other configuration options for the runtime (for example, garbage collection type).
The application's dependencies, which are copied from the NuGet cache into the output folder.

The dotnet publish command's output is ready for deployment to a hosting system (for example, a server, PC, Mac, laptop) for execution. It's the only officially supported way to prepare the application for deployment. Depending on the type of deployment that the project specifies, the hosting system may or may not have the .NET shared runtime installed on it.

## External Resources

-[Microsoft](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-publish)

---

-[Back to Home!](../README.md)
