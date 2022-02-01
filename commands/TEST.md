# Dotnet Test

The terminal describes the dotnet test command as "Run unit tests using the test runner specified in a .NET project"

# Microsoft Description

The dotnet test command is used to execute unit tests in a given solution. The dotnet test command builds the solution and runs a test host application for each test project in the solution. The test host executes tests in the given project using a test framework, for example: MSTest, NUnit, or xUnit, and reports the success or failure of each test. If all tests are successful, the test runner returns 0 as an exit code; otherwise if any test fails, it returns 1.

For multi-targeted projects, tests are run for each targeted framework. The test host and the unit test framework are packaged as NuGet packages and are restored as ordinary dependencies for the project.

# Microsoft link

## -[Microsoft](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-test)

-[Back to Home](./README.md)
