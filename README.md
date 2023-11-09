# Commands

```bash
dotnet new sln --name CSharp.Nutshell
```

```bash
dotnet new console --name CSharp.Nutshell.Console
```

```bash
dotnet sln CSharp.Nutshell.sln add CSharp.Nutshell.Console/CSharp.Nutshell.Console.csproj
```

```bash
dotnet run
```

```bash
dotnet run --project CSharp.Nutshell.Console/CSharp.Nutshell.Console.csproj 
```

```csharp
git restore --staged CSharp.Nutshell.Console/obj
git rm -r CSharp.Nutshell.Console/obj
```