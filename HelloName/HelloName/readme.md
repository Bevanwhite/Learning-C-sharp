# Markdown File

### Main Method
* The Main method is the entry point of a c# application
	* It is where the program control starts and ends
	* exceptions - library projects and windows services projects
* There can be only be one entry point of a c# application
* Main is declared inside a class or struct.
* Main must be static.
* The enclosing class or struct is not required to be static.
* Main can either have a void or int return type.
* it can be declared with or without a string[] array parameter that contains command-line arguments

### dotnet framework version relase dates
* NET Framework 1.0 - 2002-01-15
	* 1.0 SP1 - 2002-03-19
	* 1.0 SP2 - 2002-08-07
	* 1.0 SP3 - 2004-08-30
* NET Framework 1.1 - 2003-04-09
	* 1.1 SP1 - 2004-08-30
* NET Framework 2.0 - 2005-10-27
	* 2.0 SP1 - 2007-11-19
	* 2.0 SP2 - 2008-08-11
* NET Framework 3.0 - 2006-11-06
	* 3.0 SP1 - 2007-11-19
	* 3.0 SP2 - 2008-08-11
* NET Framework 3.5 - 2007-11-19
	* 3.5 SP1 - 2008-08-11
* NET Framework 4.0 - 2010-04-12
* NET Framework 4.5 - 2012-08-15
	* 4.5.1 - 2013-10-17
	* 4.5.2 - 2014-05-05
* NET Framework 4.6 - 2015-07-20
	* 4.6.1 - 2015-11-30
	* 4.6.2 - 2016-08-02
* NET Framework 4.7 - 2017-04-05
	* 4.7.1 - 2017-10-17
	* 4.7.2 - 2018-04-30
* NET Framework 4.8 - 2019-04-18
	* 4.8.1 - 2022-08-09

# dotnet core version and release dates 
Version Number |Release Date |End of Support 
| :--- | :---: | :---:
1.0 	|2016-06-27 	|2019-06-27 	
1.1 	|2016-11-18 	|2019-06-27 	
2.0 	|2017-08-14 	|2018-10-01 	
2.1 long-term support 	|2018-05-30 	|2021-08-21[7] 	
2.2 	|2018-12-04[8] 	|2019-12-23[9] 	
3.0 	|2019-09-23[10] 	|2020-03-03[9] 	
3.1 long-term support 	|2019-12-03[11] 	|2022-12-03
5.0 	|2020-11-10[12] 	|2022-05-08 	
6.0 long-term support 	|2021-11-08[13] 	|2024-11-08 	
7.0 standard-term support[14] 	|2022-11-08[15] 	|2024-05-14 
8.0 long-term support[16] 	|2023-11-14[17] |2026-11-10


* `dotnet --version` - gives version of the dotnet 
* `dotnet --info` - details of sdks, runtimes, many other stuff
* `dotnet new console -n HelloNameCLI -f netcoreapp2.1` create console application using command line
* `cd HelloNameCLI` - to go into the project that you created.
* `dotnet run` - to run the project
* `notepad program.cs` - to change the code using notpad
* `explorer .` - to open the file explorer

# .Net Assembly
* Assemblies are the building blocks of .NET Freamwork applications.
* They form the fundermetal unit of deployment, version control, reuse, activation scoping, and security permissions
* An assembly is a collection of types and resources that are built to work together and form a logical unit of functionality.
* To the runtime, a type does not exist outside the context of an assembly.
* A .net assembly can be an excutable file(with a .exe file extension) or a dynamic linked library file(with a .dill file extension)
