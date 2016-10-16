Homework Log:

Thinking About Expects:
koans 1-3: So far so good!
Finished off strong.

Thinking About Arrays:
koan 6: When you have a () after an array number ...denotes? that at the index is a function... you expect the array value to be the product of the function.
object["key"]: same as object.key.

koan 7-8: Nothing to note

koan 9: If you pass in the same index for both params of the array.slice() method, you'll get an empty array. Also, if you pass a higher index in the first param and a lower index in the second, you'll get an empty array. The second param/index in the array.slice method is NOT kept in the slice.

koan 10: Nothing to note.

koan 11: Had to research Array.pop - it returns the last value in an Array after removing it from the Array.

koan 12: Also had to look up Array.shift - the same as pop but the first instead of the last. Array.unshift adds a value to the first element of the array.

Thinking About Functions:

koan 13-15: Nothing to note.

koan 16: This one is hard to wrap my head around. Not sure how to look up an explanation for this syntax either. **Would love an explanation of this one!** I was able to finish the test and I see how the numbers add up, but an explanation of how the function actually works would be great.

koan 17: Nothing to note.

koan 18: I understand what is happening with praiseSinger and appendRules. The syntax of defining a variable with { function: method } is new and I would like a little more explanation. givePraise is not asking for any parameters, but it's using the parameter its given as the parameter for its method. Interesting..

Thinking About Mutability:

koan 19: Pretty straightforward.

koan 20: Starting to get confused between the something.something syntax. Sometimes it's a method... but I think the same syntax is used to refer to Object Properties... so .firstname is not a method of the Person Constructor but is referencing the object property of aPerson? I think?

koan 21: Made sense to me!

koan 22: Learned that you can't change the properties of a Constructor once they are defined. If you change the properties and then remake the constructor they will be changed.

Thinking About Higher Order Functions:

koan 23: Made sense but still not sure what exactly underscore is. Will look into it when I inevitable get more confused!

koan 24: Easy enough

koan 25: "reduce boils down a list of values into a single value" from UnderscoreJS page. i.e. 3+2+1 = 6

koan 26: forEach "Iterates over a list of elements, yielding each in turn to an iteratee function. The iteratee is bound to the context object, if one is passed."

koan 27: all "Returns true if all of the values in the list pass the predicate truth test. Short-circuits and stops traversing the list if a false element is found."

koan 28: any "Returns true if any of the values in the list pass the predicate truth test. Short-circuits and stops traversing the list if a true element is found."

koan 29: range "A function to create flexibly-numbered lists of integers, handy for each and map loops. start, if omitted, defaults to 0; step defaults to 1. Returns a list of integers from start (inclusive) to stop (exclusive), incremented (or decremented) by step, exclusive. Note that ranges that stop before they start are considered to be zero-length instead of negative — if you'd like a negative range, use a negative step."
I'm not sure why the array ends 1 before the number named for the end. **Also not sure why there is a space before the first value.**

koan 30: flatten "Flattens a nested array (the nesting can be to any depth). If you pass shallow, the array will only be flattened a single level." **These ones don't have a space before the first value... what gives?**

koan 31: "Calling chain will cause all future method calls to return wrapped objects. When you've finished the computation, call value to retrieve the final value." First the array is flattened to be easy to deal with, then map adds 1 to each value, then reduce adds them all together.
