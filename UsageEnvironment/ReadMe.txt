========================================================================
    STATIC LIBRARY : UsageEnvironment Project Overview
========================================================================

AppWizard has created this UsageEnvironment library project for you.

No source files were created as part of your project.


UsageEnvironment.vcxproj
    This is the main project file for VC++ projects generated using an Application Wizard.
    It contains information about the version of Visual C++ that generated the file, and
    information about the platforms, configurations, and project features selected with the
    Application Wizard.

UsageEnvironment.vcxproj.filters
    This is the filters file for VC++ projects generated using an Application Wizard. 
    It contains information about the association between the files in your project 
    and the filters. This association is used in the IDE to show grouping of files with
    similar extensions under a specific node (for e.g. ".cpp" files are associated with the
    "Source Files" filter).

/////////////////////////////////////////////////////////////////////////////
Other notes:

AppWizard uses "TODO:" comments to indicate parts of the source code you
should add to or customize.

UsageEnvironment
The "UsageEnvironment" and "TaskScheduler" classes are used for scheduling deferred events, 
for assigning handlers for asynchronous read events, and for outputting error/warning messages. Also,
 the "HashTable" class defines the interface to a generic hash table, used by the rest of the code.
  
These are all abstract base classes; they must be subclassed for use in an implementation. These 
subclasses can exploit the particular properties of the environment in which the program will 
run - e.g., its GUI and/or scripting environment.


/////////////////////////////////////////////////////////////////////////////


usage£º
1¡¢mediaServer
	1)using vlc play, using url, which is rtsp://host_ip+file_name.

2¡¢proxyServer
	1)proxyServer url(rtsp)
	2)using vlc play, using url, which is printed to screen by proxyServer
