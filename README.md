# Steps To compile & run UDP_Client & UDP_Server in Windows Machine:

-> The program tagged with the containing file contains UDP_Client program in Windows called "Winsock Programming". 
-> Steps For Compilation in Windows Machine
     1. Save the file in Windows file explorer in some location with (.c) extension.
     2. Now make sure you have installed MinGW in your Machine.
     3. To ensure proper installation of MinGW in your machine, type gcc --version in your Command Window.
     4. The above returns the following results with changes in version number as:
       GCC (MinGW.org GCC-6.3.0-1) 6.3.0
       Copyright (C) 2016 Free Software Foundation, Inc.
       This is free software; see the source for copying conditions.  There is NO
       warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
     5. Now Enter the command ->cd (Location of folder contains the file.c)
     6. Now to source to the particular drive as:
         A drive : -> a:
         B drive : -> b:
         C drive : -> c:
                :
                : 
                :
         Y drive : -> y:
         Z drive : -> z:
      7. Now For Compiling the code Enter the command as:
          -> gcc file_name.c -o new_file_name -lws2_32
      8. Now after sucessfull  compilation, an (.exe) file will be created with name (new_file_name.exe),
      9. To run the file, Enter the command below & Its done. 
          ->.\new_file_name
     10. Now to close to exit the code, Press CTRL+C.
  
  # SameerMubarakShaik
