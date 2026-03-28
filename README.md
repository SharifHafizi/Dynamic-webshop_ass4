# Dynamic webshop_ass4

Description on how to make this project as part of our assignment
In this assignment, you will add some dynamic functionality to your page.

Sorting and search
Username check on registration
Submission
In this assignment, you should extend the application from assignment 3. Copy your solution to assignment 3 to the folder assignment-4 and add the following functionality:

Sorting and search
You need to implement sort and search functionality for a collection of items. Sort and search should apply to the same collection.

Sorting and search should be implemented in JavaScript. No network calls should be necessary for sorting and search.
Sorting and search should use a JavaScript representation as the source of truth, not the DOM elements. I.e., search in an array of objects and then display the results, rather than searching in the DOM structure.
Search should support multiple keywords, i.e., a search for "hello world" should return all items that contain both the words "hello" and "world".
There must be at least 3 sorting options.
The interface must show according to which criteria the collection is currently sorted.
The sorting criteria should be stored in local storage. On revisiting the page, sorting criteria should be applied.
Username check
Your application should validate usernames on the registration form. The validation should include a check whether the username is taken. This check should be implemented using an AJAX request.

When the user types his username in the registration form, make an AJAX request to the web server, asking whether the username is taken. This should happen without the user submitting the form.
If the username is taken, display an error message on the username input field.
The error needs to be displayed on the page, not as an alert.
Once the user has a valid username, the error should disappear.
It should not be possible to submit the form if the username is not unique.

