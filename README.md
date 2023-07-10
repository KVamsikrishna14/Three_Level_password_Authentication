# **Three Level Password Authentication System.**
_This project is made to implement three levels of passwords for mainly windows folders to simply secure windows folders. So that no one can read or write on that folder directly without entering the password or simply without unloacking the folder._

## This system have three levels of passwords showen bellow:

### Level 1 Text Password
_For text password it is a simple text based password to pass the level 1._


### Level 2 Color Combination
_here in the Color Combination password there is basically three colors red green blue(RGB) where user can set different combination of colors by clicking on those colors._


### Level 3 Picture Password
_here in the Picture Password the user should select a particular spot in an image if the user selects the same pot which he selected while signing up then the user is given access to the file._

### locking folder:
_the user after authenticating can lock or unlock a folder by selecting the folder._


## Advantages of this Application
- This application provides the aditional security to the windows folders.
- This application have an easy to use interface for interacting with this application.
- It provides additional security to folders so that without unlocking the folder no one can delete, read, write, move or copy the folder.

## To run this project for further development:
- Download and install Visual Studio.
- Open the Visual Studio with the admin privilege for FolderLock feature to run successfully.
- Create your own local Sql database with three tables in the visual studio:- 
- the names of the tables should be same as given below!
- LOGIN: USERNAME:varchar(50) PASSWORD:varchar(50) --no primary key
- COLOR: val:varchar(MAX) --no primary key
- picture: picture:int --no primary key
- After that copy the 'connection string' of the database you created.
- Go to the main.cs file and paste the connection string you just copied in the format showen below:-
- SqlConnection = new SqlConnection(@"Your Connection String");
- Thats it now save all files and now you can run the project.
- Thus you can lock and unlock folders in your computer using this project.
----

