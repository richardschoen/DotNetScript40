# DotNetScript40
DotNet Scripting for VB and C# - Forked from NScript project on CodeProject and Compiled Under .Net 4.0

This is a nice way to create dynamic VB or C# scripts that can be run as Console apps and integrated with other applications.

Original NScript CodeProject site link:
http://www.codeproject.com/Articles/3207/NScript-A-script-host-for-C-VB-NET-JScript-NET

Description
The project code has been renamed to DotNetScript40 and has been compiled under .Net 4.0, however I believe the software also has a .Net 2.0 dependency for use of the old VSA scripting DLL from .Net 2.0.

The DotNetScript40 solution has three projects:
DotNetScript40.exe - a C# console application for running .CS/.NCS scripts or .VB/.NVB scripts.
DotNetScriptW40.exe - a C# windows application for running .CS/.NCS scripts or .VB/.NVB scripts.
DotNetScriptLib40.DLL - a C# class library for running .CS/.NCS scripts or .VB/.NVB scripts.

DotNetScript40 and DotNetScriptW40 are very much similar to each other; the former can be used to run scripts that can output to console. DotNetScript40 shows error messages in console where as DotNetScriptW40 shows error messages using message boxes. It is DotNScriptW40 which can be associated with file extensions. Since there is lot of code that is shared by the two executables the common code is compiled in DotNetScriptLib40 and both the executables refer to this class library.

Sample usage: DotNetScript40.exe [ScriptFile.ncs/.nvb] [Parm1 Parm2]
DotNetScript40.exe hello.nvb
