========================================================================
    WIN32 Application Program：pacman Developer documentation
========================================================================

Get source code
You can get the source code for your pacman application by:
Download the source code file from the repository
Clone the source code libraries from the repository using the Git tool
If your system uses multiple repositories or submodules, make sure you get all the relevant source code.
/////////////////////////////////////////////////////////////////////////////
Layout of the directory structure
The directory structure of the application is as follows:
Ssrc /: contains the application source code
The res /: Contains application resource files such as icons, bitmaps, and cursors
Test /: contains the test file for the application
The doc /: A document file containing the application
Source files, tests, documents, and data files can all be found in their respective directories.

Pacman Content of each file of the application：
pacman.vcxproj
This is the main project file for the VC + + project generated using the Application Wizard, which contains version information about the Visual C + + that generated the file, as well as information about the platform, configuration, and project features selected using the Application Wizard.
pacman.vcxproj.filters
This is the VC + + project filter file generated using the Application Wizard. It contains the association information between the project file and the filter. In IDE, files with similar extensions are displayed in groups under specific nodes by this association.for instance,". The cpp'file is associated with the Source File filter.
pacman.cpp
This is the main application source file.
The Application Wizard has created the following resources:
pacman.rc
This is a list of all of the Microsoft Windows resources used by the program. It includes the icons, bitmaps, and cursors stored in the RES subdirectory. This file can be edited directly in Microsoft Visual C + +.
Resource.h
This is a standard header file that can be used to define a new resource ID. Microsoft Visual C + + will read and update this file
pacman.ico
This is the icon file used as the application icon (32x32). This icon is included in the primary resource file, pacman.rc.
small.ico
This is an icon file containing a smaller version of the application icon (16x16). This icon is included in the primary resource file, pacman.rc.
Other standard documents:
StdAfx.h, StdAfx.cpp
These files are used to generate a precompiled header (PCH) named pacman.pch, files, and a precompiled type file named StdAfx.obj.
Other notes:
The Application wizard uses the TODO: note to indicate the portion of the source code that should be added or customized.
/////////////////////////////////////////////////////////////////////////////
Build software
You can build the pacman application using Visual C + +. Please open the main project file pacman.vcxproj and select the desired platform and configuration. Then, all the components of the application are generated using the Build a button on the Visual C + + toolbar. The generated application will be located in the bin / directory of the application folder.
/////////////////////////////////////////////////////////////////////////////
testing software
You can test the application using the test cases in the test folder. Before running the test case, make sure that you have built the application successfully. To run a test case, open Visual C + +, load the project, select the Tests tab, and then select Run All Tests.
/////////////////////////////////////////////////////////////////////////////
Add a new test
To add a new test case, create a new test file in the test folder. Use the naming convention / schema to name the new test so that other developers can easily identify the test cases. For specific test tools, refer to the appropriate tool documentation for more information.
/////////////////////////////////////////////////////////////////////////////
Build the software version
Developers can update the version number (in the code and documentation) before calling the build system to ensure that the correct version information is displayed in the application. After the build version, it is recommended
