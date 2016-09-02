**When the user clicks on the button, the onSendMessage() method is called.**

Code within the **onSendMessage()** method creates an intent to start activity **ReceiveMessageActivity**, adds a message to the intent, and passes it to Android with an instruction to start the activity.

![](.guides/img/32diagram.png)


Android checks that the intent is OK, and then tells **ReceiveMessageActivity** to start.

![](.guides/img/33diagram.png)

When **ReceiveMessageActivity** starts, it specifies that it uses layout **activity_receive_message.xml**, and this gets displayed on the device.
The activity updates the layout so that it displays the extra text included in the intent.

![](.guides/img/34diagram.png)

