# JPEG
This repository is a simple encapsulation of the libjpeg 9b (downloaded from http://www.ijg.org/ ) in a Visual Studio 2010 solution.
In that solution, there is 2 workspaces, one for a Dynamic Library and one for a Static Library. Each one as a Debug and Release
configuration for both x86 and x64 architectures.

The repository contain :
  - the zip archive "jpegsr9b.zip" downloaded from http://www.ijg.org/files/jpegsr9b.zip
  - the folder "libjpeg-sr9b" where the zip archive was unzipped (the choice of the folder name "libjpeg-sr9b" is purely arbitrary). In this folder the file jconfig.vc was renamed into jconfig.h in order to compile with Microsoft VC
  - the folder "libjpeg" that contain the Visual Studio solution with :
      - a "binaries" folder where all binaries (.lib, .dll) are copied by post-build instructions for each workspace, configuration 
      and architecture.
      - a "dll" folder that contain the dll workspace
      - a "lib" folder that contain the lib workspace
      
Mathieu LATTES.
