# CPP_Project
# Code maintainance in multiple files 

It can be done in two ways:

1. Declaring a function in a header file then defining the function in seperate cpp file and 
   calling that function in the main.cpp file where the header file is included in both the cpp files.
2. Defining a function in one cpp file and calling it in the main.cpp file by forward declaration of that particular function.

# All about Headers
In C++, most of the header files end with the extension .h but not all of them and these header files are included within the program file with the C preprocessing directive “#include”.\
When a header file is included twice within a program, the compiler processes the contents of that header file twice which increases the execution time and this leads to an error in the program. To eliminate this error, conditional preprocessor directives are used.  

