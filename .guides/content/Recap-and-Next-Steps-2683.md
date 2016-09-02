![](.guides/img/25diagram.png)

So far we’ve coded **CreateMessageActivity** to start **ReceiveMessageActivity** when the Send Message button is pressed. 

Next, we’ll get **CreateMessageActivity** to pass text to **ReceiveMessageActivity** so that ReceiveMessageActivity can display it. 

In order to accomplish this, we’ll do three things:

1) Tweak the layout activity_receive_message.xml so that we can display the text. At the moment it’s the default layout the wizard gave us.

2) Update CreateMessageActivity.xml so that it gets the text the user inputs. It then needs to add the text to the intent before it sends it.

3) Update ReceiveMessageActivity.java so that it displays the text sent in the intent.
