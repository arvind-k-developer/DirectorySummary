                                                        DirectorySummary
                                                        ================

@Author: Arvind K.


A program that, given a directory path, it creates a summary of the files in the directory. 
Created the program in Java.

The program will be invoked as follows:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
For Java: java DirectorySummary [-r] directory_path


The optional '-r' argument indicates that the program should work recursively through subdirectories. 
If the -r option is not specified, the summary will be for the files in the given directory only, and will ignore subdirectories.
The output is a summary of file types, grouped by file extension. 
For each extension, the program will output:


<file extension>:
number of files: <number of files with given extension>
combined size: <total number of bytes for all files>
largest file: <number of bytes for largest file>
smallest file: <number of bytes for smallest file>


For example:
~~~~~~~~~~~~~~~
doc:
  number of files: 3
  combined size: 120432
  largest file: 79234
  smallest file: 10321
txt:
  number of files: ...
  
  