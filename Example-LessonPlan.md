### 2. Partners Do: Gif Searcher Activity (10 min)

* ...But first, let's create a page that allows you to search for GIFs using Giphy's API.

* Slack out the following file and instructions to students

* **File:**

  * `gif-searcher.html` in `12-GifSearcher/Unsolved/`

* **Instructions:**

  * Open the file `gif-searcher.html` in your browser. Then take a few moments to see what the application does.

  * Then fill in the missing comments for each line to describe what each section does.

### 3. Instructor Do: Review Gif Searcher Activity (10 min)

* Take a few moments to review the Activity.

* As a suggestion: call on students to explain each line of the code back to you.

* Then comment the code in real-time.

* Key points to discuss:

  * We're triggering an AJAX call upon button click.

  * The value from the input field is used to construct the API URL.
 
  * Note that we have an extra parameter to control the rating of the GIF (MPAA).

  * We then pass this query URL into our AJAX call to retrieve and generate GIFs related to the search term dynamically.

  * You may want to point out how the `gif` variable is being set to a generic `$("<img>")` and that jQuery will self-close this tag upon creation.

  * Point out that each GIF's URL being generated is completely unique. This is because the API is giving us a random URL each time.

  * Point out that if you enter the same API URL several times (i.e; <http://api.giphy.com/v1/gifs/random?api_key=dc6zaTOxFJmzC&rating=PG&tag=example>) directly into our browser, we'll get a different JSON
    each time.

* Slack out the solution when done reviewing.

* Ask students if there are any remaining questions before moving onto the next activity.
