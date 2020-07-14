# Static-Library-in-C
### Basic Steps to learn Library Linking in C/C++
1) Install Visual Studio in your machine and open developer cmd prompt in VS.
2) Let's call the file 'moo.cpp' which you want to create library for.
3) Write functions to that file.
   only compile using cl command.
   eg. cl /c moo.cpp
 4) This will create a obj file.
    To create a static library, use the following command.  
  $lib /out:static_library.lib moo.cpp
  
  eg. $lib /out:output_file_name.lib inputfile.cpp
