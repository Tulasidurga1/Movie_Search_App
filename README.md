# Movie_Search_App
# Hosted Link:-https://tulasidurga1.github.io/Movie_Search_App/
### HTML Structure:

- The code begins with the standard HTML structure.
- The <html> element is the root of the document and specifies the document's language.
- The <head> section contains metadata and references to external resources.
- The <title> element sets the title of the web page displayed in the browser.
- External styles are linked using the <link> tag.
### JavaScript and DOM Manipulation:

- JavaScript is used to add interactivity to the web page.
- DOM (Document Object Model) elements are accessed and manipulated using JavaScript.
- Key JavaScript components include:
document.getElementById(): Used to select and access elements by their unique IDs in the HTML.
- Event listeners (addEventListener): Used to respond to user interactions, such as button clicks.
- Functions: Defined to perform specific tasks, such as fetching data from an API and updating the DOM.
#  User Input and API Request:

- An input field (<input>) allows users to enter a movie name.
- When the "Search" button is clicked, a JavaScript function is called to handle the user's request.
- The user's input is retrieved from the input field.
- The fetch function is used to make an asynchronous request to an external API (OMDB API) to search for movies based on the user's input.
- The API response is handled using async/await to ensure asynchronous execution.
### API Integration:

- The code integrates with an external API (OMDB API) to fetch movie data.
- The API key is included in the request URL for authentication.
- The API responds with data in JSON format, which is parsed in JavaScript.
### Displaying Search Results:

Search results are displayed in a designated area of the web page (the "root" div).
Existing content in the "root" div is cleared before displaying new results.
For each movie found in the API response, a new HTML element is dynamically created to display the movie's poster, title, and year.
These elements are appended to the "root" div to display the search results in a grid-like format.
### CSS Styling:

- CSS (Cascading Style Sheets) is used to define the visual presentation of elements on the web page.
- CSS properties like margin, padding, font-size, and border-radius are used to style elements such as buttons and input fields.
- Elements like images (<img>), headings (<h3>), and divs are styled for consistent visual design.
### Error Handling:

Error handling is implemented to catch and log any errors that may occur during the API request or data processing.
In summary, this code demonstrates a basic web page that allows users to search for movies using an external API (OMDB API). It combines HTML for structure, CSS for styling, and JavaScript for interactivity and data retrieval. The code follows a structured approach to create a user-friendly movie search interface.
