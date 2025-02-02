Rules for the SharePoint Code Analysis Framework (SPCAF)
===============================================================

Summary
-------
This project contains custom community rules that can be used with the [SharePoint Code Analysis Framework (SPCAF)](http://www.spcaf.com). 

The rules are supported by the 

- [SPCAF Code Migration Assessment (Free)](http://url.spcaf.com/spcafma) and the 
- [SPCAF Professional Edition (Commercial)](http://url.spcaf.com/spcafpro)

The purpose of this project is to align the coding practices checked by SPCAF with the guidance defined by Microsoft e.g. in the [Office Patterns and Practices](https://github.com/OfficeDev/PnP) project in order to support developers with the transformation of their legacy full trust farm solutions (.wsp) to the SharePoint App model.

How do I get started?
---------------------

1. Download and install the free [SPCAF Code Migration Assessment](http://url.spcaf.com/spcafma) tool or [SPCAF Professional Edition](http://url.spcaf.com/spcafpro)
2. Clone this GitHub Repositiory and open the Visual Studio solution inside the SPCAF.Rules folder
3. Create/Change a rule
4. Build and replace the SPCAF.Rules.MigrationAssessment.dll in the SPCAF installation folder
5. Run SPCAF and test your rule on a WSP file.
                                     
What is SPCAF?
--------------
The SharePoint Code Analysis Framework (SPCAF) analyzes the code SharePoint solutions (.wsp) for SharePoint 2007 / 2010 / 2013
SharePoint 2013/Online apps

SPCAF includes five different analysis components for 

* Code Quality Analysis, 
* Metrics, 
* Dependency Analysis, 
* Inventory and 
* Code Migration Assessment.
 
SPCAF runs integrated in Visual Studio 2010, 2012 and 2013 or in the standalone client application that can analyze without having the source code.
Further, with SPCAF Server you can integrate the code analysis into your continuous integration process in Team Foundation Server, Visual Studio Online, TeamCity or any other automated build system. 

Links
-----
**Download (Visual Studio Gallery)**

- [SPCAF Code Migration Assessment (Free)](http://url.spcaf.com/spcafma) 
- [SPCAF Community Edition (Free)](http://url.spcaf.com/spcopce)
- [SPCAF Professional Edition (Commercial)](http://url.spcaf.com/spcafpro)

**Documentation**

- [Online Documentation](http://docs.spcaf.com)
- [Run SPCAF in VS](http://url.spcaf.com/vsintegration)
- [Rule Development (SDK)](http://url.spcaf.com/sdk)
- [Sample Rule](http://url.spcaf.com/admin/)

**Other**

- [Office Patterns and Practices](https://github.com/OfficeDev/PnP)
- [Office Developer Center](http://dev.office.com/transform)
