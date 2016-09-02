When Android tells **ReceiveMessageActivity** to start, ReceiveMessageActivity needs some way of retrieving the extra information that **CreateMessageActivity** sent to Android in the intent.

**getIntent()** returns the intent that started the activity, and you can use this to retrieve any extra information that was sent along with it. 

How you do this depends on the type of information that was sent. As an example, if you know the intent includes a String value with a name of “message”, you would use the following:

![](.guides/img/29receive.png)