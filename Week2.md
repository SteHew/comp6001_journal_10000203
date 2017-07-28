### Second Week Journal Entry

The task for this week was to create a form with labels and input boxes, and  buttons connected to javascript functions.  It's purpose is to calculate the total amount to pay, starting with the original amount then adding a tax percentage.

At first I concentrated on the **html** and the **CSS** required to set up the form with the right formatting.  The header bar and sidebar were straight forward, and creating buttons and labels was not difficult.  But I struggled to get the labels, the input boxes, and the buttons aligned correctly without resorting to `absolute` positions.  I avoided using `absolute` but eventually used a total of 7 _divs_, 8 _classes_ and an _unordered list_ to construct the form.  I'm sure there is a simpler way.

Next I turned to the functions.  With the aid of a couple of websites I managed to write code for a `calculateTotal` function in Javascript that performs a calculation using numbers inserted by the user.  However, the calculation did not produce the correct answer.

I talked with classmates who were also having difficulty with this function.  They could not produce _any_ data for a total.  A DAC7 student by the name of Alex, had been working with them for nearly an hour.  When he saw that I could get a result he then worked on my code to achieve a correct total.  He modified my function by inserting __parseFloat__ into the script.  Then my formula did produce the correct result.  He also worked on an error message to show up if someone pushes the **Calculate** button without inserting data.  But, that is not yet working.

At http://www.w3resource.com/javascript/functions/parsefloat-function.php I learned that:
>The **parseFloat** is used to get a floating value from a string.  **parseFloat** is a top-level function and is not associated with any object.

And, from https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/parseFloat
>The **parseFloat()** function parses an argument and returns a floating point number.

Also this week, I created a repository for Assessment 1, which involves writing a small application that changes background colours. Also, I created a repository for the code Jeff supplied for creating lists of names and contact details using REST API, from Week 3 class notes.  With his help, that is working, but I need to do some CSS refinements.
