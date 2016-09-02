- A **task** is two or more activities chained together.

- The < EditText > element defines an editable text field for entering text. It inherits from the Android View class.

- You can add a new activity in Android Studio by choosing File → New... → Activity.

- Each activity you create must have an entry in AndroidManifest.xml.

- An **intent** is a type of message that Android components use to communicate with one another.

- An **explicit intent** explicitly specifies the component the intent is targeted at. You create an explicit intent using 
```
Intent intent = new Intent(this, Target.class);
```

- To start an activity, call startActivity(intent). If no activities are found, it throws an ActivityNotFoundException.

- Use the **putExtra()** method to add extra information to an intent.

- Use the **getIntent()** method to retrieve the intent that started the activity.