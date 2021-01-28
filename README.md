# Developing ABP Framework applications in VsCode

In this article, I will show you my setup of VsCode how to boost up your productivity in Visual Studio Code while developing ABP Framework applications.

## Extensions

.NET Core Test Explorer

ABPx

Bracket Pair Colorizer 2

C# for Visual Studio Code (powered by OmniSharp)

C# Extensions

Code Spell Checker

GitLens — Git supercharged

Prettier - Code Formatter

Resharper 9 Keybindings

Todo Tree

Visual Studio Keymap

Razor+

Surround

## Favorite Keyboard shortcuts

| Keyboard shortcut                     | Action                                                                |
|---------------------------------------|-----------------------------------------------------------------------|
|'CTRL+SHIFT+T                          | Toggle Explorer
|'CTRL+SHIFT+E                          | Focus File in Explorer
|'CTRL+SHIFT+D                          | Debug Window
|'CTRL+SHIFT+X                          | Extensions Window
|'CTRL+SHIFT+G, G                       | Source Control window
|'CTRL+L                                | Remove Line
|'CTRL+K+D                              | Format Code
|'CTRL+K+W                              | Close all Tabs
|'CTRL+W                                | Close active Tab
|'CTRL+P                                |
|'CTRL+SHIFT+P => Git Push              | Push changes to GitHub
|'CTRL+`                                | Toggles Terminal window
|'CTRL+.                                | Quick Actions
|'F5                                    | Start HttpApi.Host application
|'SHIFT+F5                              | Stop HttpApi.Host application



## Color Theme

MONOKAI

## Useful Commands

### ABP

### Install or Update ABP ClI

```bash
    dotnet tool install -g Volo.Abp.Cli || dotnet tool update -g Volo.Abp.Cli
```

### Create a new ABP project

```bash
    abp new <YourProjectName> -u blazor/angular
```

### EntityFrameworkCore

#### Update EF Tools

The Entity Framework tools version '5.0.1' is older than that of the runtime '5.0.2'. 
Update the tools for the latest features and bug fixes.

```bash
    dotnet tool update --global dotnet-ef
```

#### Migrations


```bash
    dotnet ef migrations add <NameMigration>
```

```bash
    dotnet ef migrations remove
```

#### Database

```bash
    dotnet ef database update
```

```bash
    dotnet ef database drop
```


### Run/Stop Running a Project



#### Start/Stop Blazor project

```bash
    dotnet watch run
```

```bash
    CTRL+C
```

#### 

```bash
    dotnet clean
```

```bash
    dotnet build
```

```bash
    dotnet restore
```
