# EFPowerToolsExample
* Description:

   An example on how to use EF power tools 4 beta for visual studios 2015

* Purpose

    Clean visual studios project that uses Entity Framework Power tools
* Installation

    Open the extensions folder and install the file there. Restart visual studios afterwards.
* Note

   EFPowerTools.vsix only supports visual studios 2010, 2013, and 2015. The one on the website [link](https://visualstudiogallery.msdn.microsoft.com/72a60b14-1581-4b9b-89f2-846072eff19d) Only does 2013 and 2015. There is a guide for adding new versions which involves zipping this installer file adding the version in the xml and unzipping. 
   
   Also this saves a great deal of time, but has some minor glitches. The .NET version must be changed each time for it to work. Right click on the project and click *properties* change the Targest framework (doesnt matter what) and then save. 
* Instructions:

    Right click on the project and look for the button below. Add the server, database credentials, and then run to generate your classes and mappings.

![Extension Image](https://github.com/lastlink/EFPowerToolsExample/blob/master/Images/reverseEngineerCodeFirst.jpg)
