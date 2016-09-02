You can add extra information to this intent that can be picked up by the activity you’re targeting so it can react in some way. To do this, you use the **putExtra()** method:
```
intent.putExtra("message", value);
```
where 'message' is a String name for the value you’re passing in, and 'value' is the value. 


![](.guides/img/28diagram.png)

The putExtra()method is overloaded, so 'value' has many possible types. As an example, it can be a primitive such as aboolean or int, an array of primitives, or a String. 

You can use putExtra() repeatedly to add numerous extra data to the intent. If you do this, make sure you give each one a unique name.
