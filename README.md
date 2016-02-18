# web_lab6
Web Lab 6: Learning basic JQuery

## Essentials

### Part 1: Use this sample web page. https://github.com/minneapolis-edu/week5-jquery-examples/blob/master/lab-5-q2.html

Use JQuery selectors to:

    Make the <span> elements bold when the page loads 
    Give the <h2> elements a green backgound when they are clicked on
    Make the <p> elements disappear when you hover over them with the mouse.
    When the id="h1_blue" button is clicked, make all of the H1 elements blue.
    When the id="remove_not_important" button is clicked, remove the li items with class = "not_important"

### Part 2: Create a web page with an example table, perhaps like this:


<table>
  <tr><th>Animal</th><th>Color</th></tr>
  <tr><td>Zebra</td><td>Black and white</td></tr>
  <tr><td>Tiger</td><td>Black and orange</td></tr>
  <tr><td>Clownfish</td><td>Orange and white</td></tr>
</table>

Use JQuery selectors to make the table header row background purple; and then the backgrounds of the rows alternatively blue and green. (Or, use other colors of your choice).

### Part 3:  Compare your part 3 (striped table) JQuery page to JavaScript and CSS. Create two alternative versions of the same page.

    Can you create a striped table with just CSS? You can do it entirely in CSS: https://www.w3.org/Style/Examples/007/evenodd.en.html
    Can you do the same with just JavaScript?

Don't add odd/even class attributes to your table, you should add the stripes entirely in code or CSS. 

Think about the pros and cons of each approach. In what situations would each method - CSS, JavaScript, JQuery - be most appropriate? How much does it matter when you use which method?



## Advanced

### Part 1: To Do list in JQuery

Create a web page with an empty list, and an input box. You will use this to create a to do list. When you type something in the input box, it will be added to the list. 

Decide on one style to represent items that are not done.

Decide on another style to represent items that you have done.  Create a style sheet for both of these styles.

When you click on one of the list items, it should toggle between done and not done. You should use the toggleClass method to add a class; so that the appropriate CSS style is applied.

Add a button to remove the items you have done. When you click the button, all of the items that are done will be removed.

### Part 2: To Do List, save done items:

Start with Part 1. Add JQuery code so that when you click the remove button, add this list item (or items) to a table on the same page; with two columns: the text of the item, and the date that you marked it done.

### Part 3: To Do List Animation:

Use the previous program. Use fade or slide to animate the list items being deleted from the list and being added to the table.
