# Experiment to use item templates

To replicate install the src/templates/extensions template and do the following (from the repo root directory):

1. dotnet new --install ./src/templates/extensions
2. cd ./gen/item-template
3. dotnet new console
4. dotnet new stringext
5. Modify the Program.cs to use newly added .Reverse() method
6. dotnet run

Now uninstall

`dotnet new --uninstall src/templates/extensions` 
