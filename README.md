# EFSample
This solution is an extension of HUi project and includes an early draft sample of Microsoft Entity Framework Concept. I do not remember the actual date of the code developed by me. The database is from 2012 but it includes modules as old as from 2000. I met with EF in 2014 (pity) and it was really easy for me to get used to do with it as a function of this code. 

Please do not get me wrong. This code is very simple and lean to be compared to EF itself. But it is a nice and clear example to demonstrate what EF is and why it was developed (the purpose of EF). I think the main data access algorythm is very similar.

This solution includes a VBA Class to manage SQL queries. The idea was to implement the functionality of "Stored Procedures" within the code. The name of the VBA class module is "CStoredp".

Entity Framework (EF) is the recommended data access technology from Microsoft for .NET projects. The first version of Entity Framework was included in Visual Studio 2008 SP1 and .NET Framework 3.5 SP1 :
https://msdn.microsoft.com/en-us/library/hh913624(v=vs.113).aspx

This solution is dependent on Microsoft Data Access Objects (DAO) Version 3.6. The required DLL is included with the package.
