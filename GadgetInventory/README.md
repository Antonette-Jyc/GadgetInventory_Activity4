# Gadget Inventory System
COMP 019 – Activity 4: Application Development using MVC

ASP.NET Core MVC gadget inventory using an in-memory list, data annotations, Razor views, and Tag Helpers. Initial records: Apple iPhone 15 and Samsung Galaxy S24.

## Run
Requires .NET 8 SDK (or compatible .NET 8 environment).

```bash
dotnet restore
dotnet run
```

Open the localhost URL printed by `dotnet run`, followed by `/Gadget`.

## Test
1. Open Gadget Inventory and confirm the two initial rows.
2. Add a gadget with a brand, model name, and price from 1 to 5000.
3. Try blank brand/model and a price outside the range; the form should display validation messages and not add a record.
4. Restarting the app resets the in-memory inventory.

## GitHub submission
Initialize a Git repository, commit the project, publish it as a public repository, and submit your own repository URL to the class submission bin.
