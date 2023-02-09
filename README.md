# The Joke Factory!
Interative JavaScript web app allowing users to fetch jokes from an external joke API.
<br></br>
[Deployed version can be found here](https://conrad-e-code.github.io/The-Joke-Factory/)<br>

## Features:
Joke of the Day:
- When the page is loaded it fetches a random joke from the API and renders it, properly formatted, to the screen.

Random Joke Button:
- Fetches a new random joke and renders it to the page.

Jokes By Category:
- Buttons are rendered to the page allowing users to select a joke category. Once Selected, the button will fetch 10 jokes from the API and render them   to the page one at a time. Users then scroll through the jokes using the left and right arrow keys. Upon reaching the end of the list of jokes, If a user scrolls forward again, 10 additional jokes will be fetched from the category allowing users to endlessly cycle through the jokes in a category.

Submit A Joke:
- A dynamically rendered form allowing users to send properly formatted jokes inside a POST request to the external API. Renders Server Response to the page as an alert.

In this project We were able to successfully communicate with an external API with GET and POST requests. We were able to conform to the limitations of the preexisting API without sacrificing the user experience by getting creative with our JavaScript functionality and utilizing available endpoints.

## API Documentation:
Joke API: https://v2.jokeapi.dev/

## Authors
Liv Nelson, Bryan Sun, Conrad Etherington
