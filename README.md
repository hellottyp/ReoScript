ReoScript
=========
**Script language interpreter for .Net programs**

ReoScript is a JavaScript like script language interpreter implemented in C#. It be designed for inclusion in applications that require a built-in, easy to use, scalable script language with no dependencies other language like C/C++.

## Features

- Fully JavaScript statements and operators implement
- Supports JSON and Array literals
- Data exchange with .Net CLR
- Property Extension and Function Extension
- Access .Net object with DirectAccess
- Using .Net Types and Event Binding

ReoScript is not completely compliant to JavaScript/ECMAScript standard, it has stricter syntax check and own additional syntax, function and object in order to enhance usability of data exchange. 

ReoScript provides a simple script Editor it can be used to write and execute script directly. The Editor can also be included in application and provided to end-user.

## Hello World!

1. Download or build the following DLLs, add they into reference list of target project

    Antlr3.Runtime.dll
    Unvell.ReoScript.dll

2. Import the following namespace
    
    using Unvell.ReoScript;

3. Create ScriptRunningMachine and run script
    
    ScriptRunningMachine srm = new ScriptRunningMachine();
    
    srm.Run("alert('hello world!');");

    (Note that last semicolon in ReoScript is required)

## Third-Party

The following softwares may be included in this product:

- ANTLR v3
- FastColoredTextBox

## License

ReoScript and ReoScript Editor released under GNU Lesser General Public License (LGPLv3).