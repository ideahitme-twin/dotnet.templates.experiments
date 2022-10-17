# Experiment to use templates with parameters

To replicate install the src/templates/parameters template and do the following (from the repo root directory):

1. dotnet new --install ./src/templates/parameters
2. cd ./gen/parameters
3. dotnet new parameters -H Yerken --force 
The template "Example templates: with parameters" was created successfully.


$ cat Program.cs 
// See https://aka.ms/new-console-template for more information
Console.WriteLine("Hello, Yerken!");


