# No-Screenshot Security for Android
Android library to prevent users from using the screenshot feature.

___________________________________________________________________________________
HOW TO USE IN YOUR ANDROID APP
___________________________________________________________________________________

follow these instructions for importing the .aar:
http://dominoc925.blogspot.com/2015/09/how-to-create-and-use-android-archive.html 

add these permisions in your android manifest:
  \<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
  /<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />

class "NoScreenshot" has two function calls:
  NoScreenshot object = new NoScreenshot();
  object.start(final Activity app); // This will disallow screenshots
  object.stop(); // This will allow screenshots
 
 Vuala! You are now in control of wheather or not your user takes a screenshot
