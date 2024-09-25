# Demonstration of Activity Life Cycle using Log message, Snackbar Message and Toast Message.
> Let's talk about the activity life cycle a bit before diving into the coding part.
**Activity**: An activity is one screen of an app, basically whatever you sees in your screen can be said as one activity or say your application. Now imagine what happens when you open another app or go to the home page of your device?.. The Answer is the activity goes to different phases such as pause, stop etc, Small info of each phase is mentioned below:

- onCreate called when activity is first created.
- onStart called when activity is becoming visible to the user.
- onResume called when activity will start interacting with the user.
- onPause called when activity is not visible to the user.
- onStop called when activity is no longer visible to the user.
- onRestart called after your activity is stopped, prior to start.
- onDestroy called before the activity is destroyed.


## Demonstration / Practical
> Enough with theory, let's understand it more by performing one small practical.

**__Steps__**:
- Create New-project in Android studio.
  - Go to file -> New -> Empty views Activity (In Android Studio).
- Go to the `activity_main.xml` file and add the below-mentioned code.
  - Click [here](app/src/main/java/com/example/a22012011085_pr2/MainActivity.kt) for reference.
- Go to the `MainActivity.kt` file, add some code, and make changes in the onCreate() method as mentioned below.
  - Click [here](app/src/main/res/layout/activity_main.xml) for reference.
  
