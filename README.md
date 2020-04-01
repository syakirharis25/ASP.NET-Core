# ASP.NET-Core
My works related to ASP.NET Core open-source web framework developed by Microsoft and the community.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [ASP.NET Core developers.](#developers)
4. [GitHub notes.](#github)
5. [GitHub repository calculation.](#calculation)

<a name="introduction"></a>
## 1. Introduction.
<img src="C_Sharp.png" height="110">
C# (pronounced see sharp, like the musical note C♯, but written with the number sign) is a general-purpose, multi-paradigm programming language encompassing strong typing, lexically scoped, imperative, declarative, functional, generic, object-oriented (class-based), and component-oriented programming disciplines. It was developed around 2000 by Microsoft as part of its .NET initiative, and later approved as an international standard by Ecma (ECMA-334) and ISO (ISO/IEC 23270:2018). Mono is the name of the free and open-source project to develop a compiler and runtime for the language. C# is one of the programming languages designed for the Common Language Infrastructure (CLI).
<br /><br />
C# was designed by Anders Hejlsberg, and its development team is currently led by Mads Torgersen. The most recent version is 8.0, which was released in 2019 alongside Visual Studio 2019 version 16.3.

<a name="references"></a>
## 2. Official references websites.
Microsoft official website : https://www.microsoft.com <br />
C# official documentation by Microsoft : https://docs.microsoft.com/en-us/dotnet/csharp/ <br />

**_C# related tools_** <br />
Visual Studio Community : https://visualstudio.microsoft.com/vs/community/ <br />

**_C# questions and answers_** <br />
Stack Overflow questions and answers website : https://stackoverflow.com

**_C# documentation by docs.microsoft.com_** <br />
using (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/using <br />
Namespaces (C# Programming Guide) : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/namespaces/ <br />
Classes (C# Programming Guide) : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/classes <br />
static (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/static <br />
void (C# reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/void <br />
Main() and command-line arguments (C# Programming Guide) : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/main-and-command-args/ <br />
Strings (C# Programming Guide) : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/strings/ <br />
Optimize Visual Studio performance : https://docs.microsoft.com/en-us/visualstudio/ide/optimize-visual-studio-performance?view=vs-2019 <br />
Types and variables : https://docs.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/types-and-variables <br />
Integral numeric types (C# reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types <br />
char (C# reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/char <br />
Floating-point numeric types (C# reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/floating-point-numeric-types <br />
bool (C# reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/bool <br />
Arrays (C# Programming Guide) : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/ <br />
Static Classes and Static Class Members (C# Programming Guide) : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/static-classes-and-static-class-members <br />
if-else (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/if-else <br />
Boolean logical operators (C# reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/boolean-logical-operators <br />
switch (C# reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/switch <br />
break (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/break <br />
while (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/while <br />
do (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/do <br />
Multidimensional Arrays (C# Programming Guide) : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/multidimensional-arrays <br />
Document your code with XML comments : https://docs.microsoft.com/en-us/dotnet/csharp/codedoc <br />
try-catch (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/try-catch <br />
try-finally (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/try-finally <br />
try-catch-finally (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/try-catch-finally <br />
Objects (C# Programming Guide) : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/objects <br />
public (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/public <br />
new operator (C# reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/new-operator <br />
private (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/private <br />
get (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/get <br />
set (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/set <br />
Inheritance in C# and .NET : https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/inheritance <br />
virtual (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/virtual <br />
override (C# Reference) : https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/override <br />

**_C# documentation by devblogs.microsoft.com_** <br />
What character escape sequences are available? by Jon Skeet : https://devblogs.microsoft.com/csharpfaq/what-character-escape-sequences-are-available/ <br />

**_C# questions and answers by Stack Overflow_** <br />
What is “string[] args” in Main class for? by Stack Overflow : https://stackoverflow.com/questions/552796/what-is-string-args-in-main-class-for/45752359 <br />
What are the benefits of using C# vs F# or F# vs C#? [closed] by Stack Overflow :https://stackoverflow.com/questions/952318/what-are-the-benefits-of-using-c-sharp-vs-f-or-f-vs-c <br />
c#: getter/setter by Stack Overflow : https://stackoverflow.com/questions/6709072/c-getter-setter/38447109 <br />

**_C# related articles_** <br />
C# Programs by javatpoint : https://www.javatpoint.com/csharp-programs <br />

<a name="developers"></a>
## 3. C# developers.
Anders Hejlsberg : https://github.com/ahejlsberg, https://twitter.com/ahejlsberg <br />
Mike Dane : https://github.com/mikedane <br />
Jon Skeet : https://github.com/jskeet, https://twitter.com/jonskeet <br />
 
<a name="github"></a>
## 5. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/C-Sharp.git
$ cd C-Sharp/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 6. GitHub repository calculation.
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
C#                              35            115             22            783
JSON                             6              0              0            172
Markdown                         1             12              0             86
XML                              2              0              0             21
MSBuild script                   1              2              0              6
-------------------------------------------------------------------------------
SUM:                            45            129             22           1068
-------------------------------------------------------------------------------
```
Refer to : https://github.com/syakirharis25/cloc
