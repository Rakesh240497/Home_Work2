# Home_Work2

The main aim of the program is to get the file hierarchy of the a directory according the given conditions in commmand line arguments

First we check for the all the error while opening the file. 
By opening the file using opendir we check for the errorrrs
 
 If there are no errors we than go for conditions that are given in the command line. 
 
 By using the loop up table and swict case we check for the conditions and the case given in the command line. 
 
 According to the conditions given we check for the case and call the functions related to that conditions 
 
 #1 
 For printing the file of the directory we go till directory is not null 
 and print the file name using dirent->d_name and for the size we call the function file_size
 
 #2
 For printing the files of the directory we go till directory is not null 
 and print the file names using dirent->d_name and check for the size that is given in the condition if the size of the file is greater than or equal to the size of the given condition we print that file. 
 
 #3
 for printing the files of the directory with sub string we go till directory is not null 
 and compare the two string file name and condition if the substring present in the filename we print that file. 
 
