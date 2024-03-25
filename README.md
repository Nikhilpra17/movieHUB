# Project Overview

## Technologies Used

- **useState and useEffect Hooks:** React's useState and useEffect hooks are utilized for managing component state and side effects respectively. They enable the dynamic rendering of content based on changes in state and facilitate the fetching of data from external APIs.

- **Axios:** Axios is used for making HTTP requests to the REST API. It simplifies the process of fetching data and handling responses asynchronously.

- **CSS:** CSS is employed for styling the user interface, including layout, color schemes, typography, and animations. Advanced CSS techniques such as flexbox and grid layout are utilized to create responsive designs and enhance visual appeal.

- **Bootstrap:** Although not explicitly used in the provided code, Bootstrap is mentioned as one of the CSS frameworks that could be utilized for responsiveness. However, the provided code demonstrates custom CSS for styling purposes.

## Functionality

- **Dynamic Movie Search:** The application allows users to search for movies dynamically by making requests to the OMDB API based on the user's input. As the user types in the search query, the application fetches relevant movie data and displays it in real-time.

- **Movie Details:** Upon selecting a movie from the search results, detailed information about the selected movie is displayed, including its title, year of release, runtime, IMDb rating, plot summary, cast, director, and genre.

- **Watched List Management:** Users can add movies to a watched list, which persists throughout the session. The watched list displays summary statistics such as the number of watched movies, average IMDb rating, average user rating, and average runtime.

- **Responsive Design:** The application is designed to be fully responsive, ensuring optimal user experience across various devices and screen sizes. Media queries and advanced CSS techniques are employed to adapt the layout and styling accordingly.

## API Integration

The application integrates with the OMDB API (Open Movie Database) to fetch movie data dynamically. The API key is provided as a constant (`KEY`) in the code, and requests are made to the API endpoint using Axios. The fetched data is then processed and displayed to the user in an organized manner.

## Advanced CSS Techniques

- **Flexbox:** Flexbox layout is utilized for creating flexible and responsive container layouts, allowing for easy alignment and distribution of elements within the application's UI.

- **Grid Layout:** CSS grid layout is used for structuring the main layout of the application, providing a grid-based structure for organizing content and achieving responsive design.

- **Custom Styling:** Custom CSS is employed for styling various UI components, including navigation bar, search input, movie cards, movie details, and watched list summary. Styling choices are made to enhance visual appeal and ensure consistency throughout the application.

Overall, the project demonstrates proficiency in building modern, responsive web applications using React.js, integrating with external REST APIs, and employing advanced CSS techniques for effective UI design and user experience.
