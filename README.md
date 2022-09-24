# Login with Email and password Firebase
Step-1 @Connect Firebase authentication into app
 Android Studio --> Tools->Firebase -> Authenticate using a custom authentication system -> Connect to Firebase( automaticatically browser goes to firebase then select project in which you want to authenticate this. Click connect then return to android studio )    -> (Adding dependency needed) add the firebase authentication SDK to your app --> Accept changes

Step -2 @ Adding JSON file of your project into your app . 
  Go to firebase in browser -> Go to Project settings -> download json file and add it to project -level into  app folder .
  
Step -3 @enable sign in with email id and password authentication into your firebase project .




#  To remove Status Bar or set full screen of Activity . 
In .java file --> getWindow().setFlags(WindowManager.LayoutParams.FLAG_FULLSCREEN,WindowManager.LayoutParams.FLAG_FULLSCREEN);
