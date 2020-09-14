# pratilipi_reading_app

Prototype for reading stories.

# SET UP :
All commands needed to set up and execute said code:
  Technology Used:
    1)Framework: Flutter (Used Version: 1.12.13+hotfix.8 • channel stable)
    2)Language Used: Dart (Used Version: 2.7.0)
    3)IDE Used: Android Studio (Used Version: 3.4)
	4)Firebase (for data)
   
  Various components of the structure of the application are explained here −
    1)android − Auto generated source code to create android application 2) ios − Auto generated source code to create ios application
    2)lib − Main folder containing Dart code written using flutter framework
    3)lib/main.dart − Entry point of the Flutter application
    4)test − Folder containing Dart code to test the flutter application
    5)test/widget_test.dart − Sample code
    6).gitignore − Git version control file
    7).metadata − auto generated by the flutter tools
    8).packages − auto generated to track the flutter packages
    9).iml − project file used by Android studio
    10)pubspec.yaml − Used by Pub, Flutter package manager
    11)pubspec.lock − Auto generated by the Flutter package manager, Pub
    12)README.md − Project description file written in Markdown format
	
# Backend :

1) User Sign Up: Sign up using Firebase with email and password with validations.
2) User Login: Login with the registered email-id password.
3) Current Viewers: Based on event listeners to listen to any update on the list of current viewers and reflect the changes every time a new user is added or removed. 
					User removal criteria : 1)If app is closed or minimized 2)User leaves the page
4) Total Read Count: Based on user email which is unique and ensures that read count is added once only for each user.



