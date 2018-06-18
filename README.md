# yield

https://stackoverflow.com/questions/14057788/why-use-the-yield-keyword-when-i-could-just-use-an-ordinary-ienumerable

Using yield makes the collection lazy.

Let's say you just need the first five items. Your way, I have to loop
through the entire list to get the first five items. With yield, I
only loop through the first five items.