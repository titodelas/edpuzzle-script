# EdPuzzle Script

This bookmarklet can fetch the answers for the multiple choice questions on any Edpuzzle assignment. It can also skip the entire video, as well as automatically answer the questions.

# Features
- Can fetch and display the multiple-choice answers for any Edpuzzle assignment
- Can automatically answer all the multiple-choice questions in an assignment
- Includes a video skipper which allows for arbitrary navigation within an assignment
- Shows various stats about the assignment
- Has a decent looking GUI
- No login or extension required
- Works on private Edpuzzle videos
- Licensed under the GNU GPL v3 license

## Installation
1. Copy the following code into your clipboard:
```javascript
javascript: if (window.location.hostname == "edpuzzle.com") {var r = new XMLHttpRequest(); r.open("GET", "https://cdn.jsdelivr.net/gh/ading2210/edpuzzle-answers@latest/script.js", true); r.addEventListener("load", function(){eval(this.responseText);}); r.send();} else {alert("Please run this on https://edpuzzle.com/assignments/[assignment_id]/watch")}
```
2. Right-click on your bookmarks bar and click "add page."
3. Set the name of the bookmark to whatever you want.
4. Paste in the code into the box for the url and save the bookmark.

## Usage
1. Navigate to any Edpuzzle assignment.
2. Make sure the url follows this format: https://edpuzzle.com/assignments/{id}/watch
3. Click on the bookmarklet to run the script.
4. If it doesn't work, make sure you allow popups from edpuzzle.com, then try again.

## License & Credits
⚠ THIS IS NOT THE ORIGINAL GIT. GO [HERE](https://github.com/ading2210/edpuzzle-answers) TO SUPPORT THE ORIGINAL CREATOR ⚠
[MIT](https://choosealicense.com/licenses/mit/)
