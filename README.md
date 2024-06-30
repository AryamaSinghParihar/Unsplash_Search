# Unsplash Image Search
Unsplash Image Search is a web application built with React that allows users to search and explore images from Unsplash's extensive collection. Users can toggle between light and dark themes, search for specific images, and view the results in a responsive gallery layout.


### Features
* Theme Toggle: Users can switch between light and dark themes for better viewing comfort.
* Search Form: Allows users to input search queries to find specific images.
* Gallery Display: Displays search results from Unsplash in a responsive grid layout.
* Loading and Error Handling: Provides feedback during data fetching and displays errors if search results are not found or if there's an issue with the API.
  
### Technologies Used
* React: Frontend library for building user interfaces.
* React Query: Library for managing and caching server state in React applications.
* Axios: Promise-based HTTP client for making requests to the Unsplash API.
* CSS Variables: Used for easy theme management and consistent styling across components.


#### API Integration
The application integrates with the Unsplash API to fetch image data based on user search queries. It utilizes Axios for making HTTP requests and React Query for efficient data fetching and caching.

#### Theme Toggle
The theme toggle component allows users to switch between light and dark themes. It uses CSS variables to dynamically adjust the color scheme of the application based on user preference.

#### Gallery Component
The Gallery component renders the search results retrieved from the Unsplash API. It displays images in a grid layout and handles loading states, errors, and empty result scenarios gracefully.

#### Search Form
The SearchForm component includes a form input where users can enter search queries. Upon submission, it updates the global state with the search term, triggering a re-fetch of image data from the API.

#### Global Context
Global state management is handled with React's Context API. The AppProvider component manages states such as dark theme preference and search term, which are accessible throughout the application via custom hooks.

#### Styling
Styling is done using CSS variables for consistent theming and responsive design. Media queries ensure that the application layout adjusts seamlessly across different screen sizes.

