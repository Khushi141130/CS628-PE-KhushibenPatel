Movie List

#Input

The application uses a predefined list of movie objects that include details such as the title, genre, and release year. It also takes input from the user through a dropdown menu, allowing them to choose whether to view all movies or filter them by a specific genre.

#Process

The component uses the useState hook to keep track of the selected genre. Based on the user’s choice, the app filters the movie list and updates what is shown on the screen. Whenever a user clicks on a movie card, a click handler is triggered to display an alert.

#Output

The result is a list of movie cards displayed in the browser. The list updates instantly based on the selected genre, showing only the relevant movies. Each card is designed in a simple and organized way, making it easy to view the movie details clearly.