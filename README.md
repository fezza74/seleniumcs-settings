# Selenium c# Settings
Settings to use Selenium c# with Visual Studio Code
***
Before all you need of [Visual Studio Code](https://code.visualstudio.com/download) (VSC), if you haven'yet!

## Table of contents
1. [Install .NET SDK](#install-net-sdk)
2. [Install C# and Nuget](#install-c#-and-nuget)
3. [Create a MSTest Project Folder](#create-project-folder)
4. [Add Selenium WebDriver](#add-selenium-webdriver) package to the TestProject

## Install .NET SDK
***
To install .net SDK click on this link (https://dotnet.microsoft.com/en-us/download/) and follow the instruction

After that, to verify the installation open the terminal and digit:

```bash
dotnet --version
```

## Install C# and Nuget
***
To install C# on VSC press `CMD+SHIFT+X`(for mac) and search for C#

Click on Install (if you haven't yet)


Repeat for the `NuGet Package Manager`

## Create a MSTest Project Folder
***
From the terminl digit this

```bash
dotnet new mstest -o FirstSeleniumTest
```

The out will be like this

```bash
The template "MSTest Test Project" was created successfully.

Processing post-creation actions...
Restoring /Users/giannifezza/Documents/HelloSeleniumTest/FirstSeleniumTest.csproj:
  Determining projects to restore...
  Restored /Users/giannifezza/Documents/HelloSeleniumTest/FirstSeleniumTest.csproj (in 233 ms).
Restore succeeded.
```
Now, in VSC, open the folder you just created

## Add Selenium WebDriver package to the TestPorject
***
TODO

[TOP](#table-of-contents)
