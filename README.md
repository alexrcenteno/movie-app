#H1Movie App
This is a movie app that allows users to search for movies and view details such as the title, release year, and plot. The app uses the Open Movie Database (OMDb) API to retrieve movie data.

## H2 Getting Started
To use the app, you will need to obtain an API key from OMDb. Once you have the key, create a .env file in the root directory and add the following line:

javascript
Copy code
REACT_APP_API_KEY=<your api key>
Replace <your api key> with your actual API key.

**To run the app, run the following commands in your terminal:**

sql
Copy code
npm install
npm start
The app should be running at http://localhost:3000.

### H3 Usage
To search for a movie, enter the title in the search bar and click the "Search" button. The app will display a list of movies that match the search query.

To view details about a movie, click on the movie in the search results. The app will display the movie's title, release year, plot, and other details.

#### H4 Code Structure
The code for the app is structured as follows:

src/App.js: The main component of the app. Renders the search bar and movie details components.
src/components/SearchBar.js: Renders the search bar and handles search queries.
src/components/MovieDetails.js: Renders the details of a selected movie.
src/utils/api.js: Contains the functions for fetching movie data from the OMDb API.
The app was built using React and styled with CSS. The axios library was used to make HTTP requests to the API.

##### H5 License
This project is licensed under the MIT License. See the LICENSE file for details.
