# Selenium c# Settings
Settings to use Selenium c# with Visual Studio Code
***
Before all you need of [Visual Studio Code](https://code.visualstudio.com/download) (VSC), if you haven'yet!

## Table of contents
1. [Install .NET SDK](#install-net-sdk)
2. [Install C# and Nuget](#install-cs-and-nuget)
3. [Create a MSTest Project Folder](#create-a-mstest-project-folder)
4. [Add Selenium WebDriver](#add-selenium-webdriver-package-to-the-testporject) package to the TestProject

## Install .NET SDK
To install .net SDK click on this link (https://dotnet.microsoft.com/en-us/download/) and follow the instruction

After that, to verify the installation open the terminal and digit:

```bash
dotnet --version
```

[TOP](#table-of-contents)

## Install CS and Nuget
To install C# on VSC press `CMD+SHIFT+X`(for mac) and search for C#

Click on Install (if you haven't yet)


Repeat for the `NuGet Package Manager`

[TOP](#table-of-contents)

## Create a MSTest Project Folder
From the terminal digit this

```bash
dotnet new mstest -o FirstSeleniumTest
```

The output will be like this

```bash
The template "MSTest Test Project" was created successfully.

Processing post-creation actions...
Restoring /Users/giannifezza/Documents/HelloSeleniumTest/FirstSeleniumTest.csproj:
  Determining projects to restore...
  Restored /Users/giannifezza/Documents/HelloSeleniumTest/FirstSeleniumTest.csproj (in 233 ms).
Restore succeeded.
```
Now, in VSC, open the folder you just created

[TOP](#table-of-contents)

## Add Selenium WebDriver package to the TestPorject
To run Selenium C# tests we can use different browsers (Chrome in this tutorial, but the steps are similar for all)

We need to:

- `Chrome browser`
- `ChromeDriver` for matching browser version is in the PATH
- `Selenium WebDriver library` is installed and configured in the test project

To do this press CMD+SHIFT+P (for mac, or CTRL+P for Windows)

Select in the bar `NuGet Package Manager: Add Package` then type `Selenium` and press Enter

Press Enter to select `Selenium.WebDriver` and then select the latest version of this

_if appears a popup, click `Restore`_

Now you are ready to get started!

[TOP](#table-of-contents)
