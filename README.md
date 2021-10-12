# Practice Grocery List

This is [Skillcrush](https://skillcrush.com/) course practice.

# Instructions

Log out the length of the groceries variable to see how many elements are in the array. The number in the console includes all elements in the array, including duplicates.

Create a variable called deleteDuplicates for a function expression with list as a parameter.

Inside the function body, declare a variable called cleanList with an empty array as a value. This empty array will hold the unique items from your groceries list. For example, because “coffee” appears twice in the groceries array, this new array will only have the first instance of coffee and will not hold the second instance.

Use for...of to loop through the groceries array, referring to each element as item.

Inside the loop, use an if statement to check if the cleanList array doesn’t already include the item. Hint: Add a not operator (!) before cleanList in the condition.

If the cleanList array doesn’t include the item, add an element to the end of the array.

Return the cleanList.

Create a variable called newGroceries and assign it to a call to the deleteDuplicates function. Pass the groceries array as an argument.

Log out the length of the newGroceries array. 

The new array length should be less than the length you logged out in step 2 because there are no duplicates. If the length isn’t less, make sure you’re only pushing elements to the empty array that it doesn’t already contain.

Loop through the newGroceries array to find the element and the index of each element. Hint: When choosing how to loop through your array, think about which tool will help you get the element AND the index of the element.

Log out a numbered list of groceries for your shopping list in the console. Remember, you don’t want the list in the console to start with 0! (See screenshot above.)
