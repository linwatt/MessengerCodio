**1)** When the app gets launched, the main activity, CreateMessageActivity starts.

![](.guides/img/20diagram.png)



**2)** The user clicks on a button.The onSendMessage() method in CreateMessageActivity responds to the click.

![](.guides/img/22diagram.png)

**3)** The onSendMessage() method tells Android to start activity ReceiveMessageActivity using an intent. Android checks that the intent is OK, and then it tells ReceiveMessageActivity to start.

![](.guides/img/21diagram.png)


**4)** When ReceiveMessageActivity starts, it specifies that it uses layout activity_receive_message.xml and this gets displayed in a new window.


![](.guides/img/23diagram.png)


