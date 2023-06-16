# Favicon Grabber

This is a simple web-based tool that allows users to retrieve the favicon (the small icon associated with a website) for a given URL. It fetches the favicon from either DuckDuckGo or Google based on the selected size.

## How to Use

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Enter the URL for which you want to retrieve the favicon in the input field.
4. Select the desired size from the dropdown list.
5. Click the "Grab" button.
6. The fetched favicon will be displayed below the input field.

## Dependencies

The Favicon Grabber tool has the following dependencies:

- `style.css`: This external CSS file contains the styling for the HTML elements.
- DuckDuckGo API: It is used to fetch the favicon when the size is set to "default".
- Google API: It is used to fetch the favicon with the specified size.

Please make sure that these dependencies are accessible and available for the tool to function correctly.

## Screenshots

### Before
<a href="https://imgur.com/PLaeKPC"><img src="https://i.imgur.com/PLaeKPC.png" title="source: imgur.com" /></a>


### After
<a href="https://imgur.com/GosPNB6"><img src="https://i.imgur.com/GosPNB6.png" title="source: imgur.com" /></a>

## Update Notes

### Version 1.1 (16-06-2023)

1. Created a separate JavaScript file:
   - The JavaScript code has been moved to a separate file named "script.js".
   - This separation improves code organization and allows for better maintainability.

2. Linked the JavaScript file to the HTML file:
   - In the HTML file (index.html), a `<script>` tag has been added at the end of the body section: `<script src="script.js"></script>`.
   - This links the HTML file to the JavaScript file, allowing the JavaScript code to be executed when the HTML file is loaded.

3. No changes to the HTML structure or styling:
   - The HTML structure and styling remain the same as in the original code.
   - The CSS file (style.css) is still being linked in the HTML file.

4. No changes to the JavaScript functionality:
   - The JavaScript functions (`isValidURL`, `startIT`, and `grabFAV`) remain the same.
   - The functionality of the Favicon Grabber tool is unchanged.
   - The code still validates the entered URL, retrieves the favicon based on the selected size, and displays the favicon in the `<img>` tag.

**By separating the JavaScript code into a separate file and linking it to the HTML file, the code becomes more modular and easier to maintain. The overall functionality of the Favicon Grabber tool remains the same, allowing users to enter a URL and retrieve the corresponding favicon.**

## Contributions

Feel free to contribute to the project or report any issues by creating a pull request or submitting an issue on the repository.

Happy favicon grabbing!
