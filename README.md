take the file name from the user.
use readline()function for the first line first.
use a while loop to printe the first line and then read the remaining lines and print it till the end of file
exit.

Here is source code of the python program to read the contents of. the program output is also shown below
a=str(input("enter the name of the file with.txt extension:")
file2=open(a,'r')'
line=file2.readline()
while(line!=""):
print(line)
line=file2.readline()
file2.close()


program explanation
user must enter a file name
the file is opened using the open()function in the read mode 
the readline() outside the while loop is used to read the first line of the file
inside the loop , the first line is first printed and then the remaining lines are read and subsequently printed.
this continues this the end of file. 
the file is then closed.
