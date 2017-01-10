# No-Screenshot Security for Android
Android library to prevent users from using the screenshot feature.

___________________________________________________________________________________
HOW TO USE IN YOUR ANDROID APP:

follow these instructions for importing the .aar:
<br>
http://dominoc925.blogspot.com/2015/09/how-to-create-and-use-android-archive.html 
<br>
<br>
add these permisions in your android manifest:
<br>
 &nbsp; &lt;uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
  <br>
 &nbsp; &lt;uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
<br>
<br>
class "NoScreenshot" has two function calls:
<br>
&nbsp;  NoScreenshot object = new NoScreenshot();
  <br>
&nbsp;  object.start(final Activity app); // This will disallow screenshots
  <br>
&nbsp;  object.stop(); // This will allow screenshots
 <br>
 <br>
 Vuala! You are now in control of wheather or not your user takes a screenshot
