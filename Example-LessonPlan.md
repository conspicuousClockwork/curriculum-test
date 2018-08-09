### 2. Partners Do: Symbol Searcher Activity (10 min)

* ...But first, let's create a page that allows you to search for information on stock symbols using the IEX Trading API.

* Slack out the following file and instructions to students

* **File:**

  * `symbol-searcher.html` in `12-SymbolSearcher/Unsolved/`

* **Instructions:**

  * Open the file `symbol-searcher.html` in your browser. Then take a few moments to see what the application does.

  * Then fill in the missing comments for each line to describe what each section does.

### 3. Instructor Do: Review Symbol Searcher Activity (10 min)

* Take a few moments to review the Activity.

* As a suggestion: call on students to explain each line of the code back to you.

* Then comment the code in real-time.

* Key points to discuss:

  * We're triggering an AJAX call upon button click.

  * The value from the input field is grabbed using `.val()` to construct the API URL.
 
  * We then pass this query URL into our AJAX call to retrieve data on the stock symbol the user inputted.

  * You may want to point out how each variable is being set to a `<p>` element and that we pass them all into the `.prepend()` function at once.

  * Point out that we also attach an `.ajaxError()` event handler to the document in case the user input can't be found.

  * The callback function will retrieve the user input at the time of the AJAX error using `.val()` again and print an error message. 

* Slack out the solution when done reviewing.

* Ask students if there are any remaining questions before moving onto the next activity.

