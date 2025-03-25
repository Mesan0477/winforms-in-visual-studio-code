# README.md
Writing WinForms in Visual Studio Code is complex. So how do we do it?

You need to download some software. These are;

- **Visual Studio Code:** 
Visual Studio Code is a program that lets you write, compile and run code. (Download Link: [Visual Studio Code](https://code.visualstudio.com/docs/?dv=win64user)) When you click on this link, Visual Studio Code will automatically be installed on your computer.

Info: This method does not work in the Web version of Visual Studio Code. For complex tasks like WinForms or running code, Visual Studio Code must be used.

- **.NET Framework:**
.NET Framework helps you create WinForms. It is also used to download Visual Studio, a paid version of Visual Studio Code.(Download Link: [.NET Framework](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net481))

## How Do I Create WinForms?

After downloading .NET Framework and Visual Studio Code, open Visual Studio Code and follow this path;

Terminal > New Terminal

or use this shortcut: Ctrl+Shift+"

**Enter this code in Terminal.**
```bash
dotnet new winforms
```
**These files are created.**
- Form1.cs
- Form1.Designer.cs
- Program.cs
- Projects.csproj
- Projects.csproj.user

Now you can create some forms from our files divided into folders.

To run your WinForms, enter the code 

```bash
dotnet run
```

into the terminal.
