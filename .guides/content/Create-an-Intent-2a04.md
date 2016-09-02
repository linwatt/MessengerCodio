Whenever you want an activity to start a second activity, you use an **intent**. It’s a type of message that allows you to bind separate objects (such as activities) together at runtime. 

If one activity wants to start a second activity, it does it by sending an intent to Android. Android will start the second activity and pass it the intent. 

The first parameter tells Android which object the intent is from, and you can use the word **'this'** to refer to the current activity. 

The second parameter is the class name of the activity that needs to receive the intent.


![](.guides/img/16code.png)