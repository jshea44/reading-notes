# Readings: HTML Lists, Control Flow with JS, and the CSS Box Model
This reading continues to iterate over the basics of html, css, and adds a bit of Javascript in the form of data structures, such as arrays, as well as data types.
## Ordered and Unordered lists.
  1. You should use an unordered list when you don't care about the order/having them numbered or having an indication of incrementing.
  2. There is an attribute called `type` that is used to change the bullet type, however this is deprecated so CSS should be used instead. 
  3. You should use an ordered list when you want the user to look at one item before looking at the other, when there is a certain meaning to the order of the items, such as steps to take for something. An unordered list should be used when it doesn't really matter what order the user looks at the items, like a grocery list.
  4. You can change the numbers to be roman numerals by setting the attribute `type="i"`. 

## The Box Model.
 1. Margin and Padding are always at odds with eachother, thinking one is more important than the other. Border stays inbetween them so they don't fight and always reminds them of their jobs. Margin keeps watch of the outside world, keeping invaders at bay. Padding watches over Content and makes sure it never wonders off or gets too close to Border.
 2. 1. Content box - This is the portion that displays your content.
    2. Padding box - This wraps around the content box as white space.
    3. Border box - This wraps around the padding box. Usually is a black line that wraps around.
    4. Margin box - This wraps around the border box as white space.

## Arrays. Operators and Expressions. Conditionals. Loops.
  1. You can store multiple data types in an array. It can be strings, numbers, booleans, null, undefined, other arrays, and objects. Anything.
  2. Yes, this is a valid array. You can access values buy using two sets of brackets. -> `myArr[index1][index2];`
  3. 1. `x += f()` - This adds before assigning.
     2. `x -= f()` - This subtracts before assigning.
     3. `x *= f()` - This multiplies before assigning.
     4. `x /= f()` - This divides before assigning.
     5. `x %= f()` - This gives the remainder from division before assigning.
  4. The result of the expression would be a string `10dog`. This is because when you try to concatinate with a string, Javascript converts the other values to strings as well. In the case of `(a + c)`, where `a = 10` and `c = false`, addition is performed here because there is a number. `false` is turned into a 0.
  5. A real world example could be in terms of clearance to access something. There would need to be a variable that indicates if someone can access something that others can not such as `hasClearance = true`. This could be something around security, or maybe something about whether or not someone can manipulate a page. So the condition could be something like `if (hasClearnace === true) {//give access} else {//do not give access}`
  6. A loop could be useful if you are trying to iterate over an array that contains a list of groceries and, in combination with an if statement, delete items that the user already has.

## Things I want to know more about
