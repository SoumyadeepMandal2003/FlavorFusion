# FlavorFusion

[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/SoumyadeepMandal2003/FlavorFusion)

FlavorFusion is a dynamic and responsive web application designed for food enthusiasts to discover new recipes. Built with React, it leverages the Spoonacular API to provide a vast collection of culinary delights. Users can search for specific dishes, browse by cuisine, or get inspired by curated lists of popular and vegetarian options.

## Features

*   **Recipe Search:** A prominent search bar allows users to find recipes by keywords.
*   **Browse by Cuisine:** Explore recipes from different culinary traditions like Italian, American, Thai, and Japanese.
*   **Curated Carousels:** The homepage features interactive carousels for "Random Picks" and "Vegetarian Picks" to inspire your next meal.
*   **Detailed Recipe Pages:** Each recipe has a dedicated page displaying its image, a summary, a list of ingredients, and step-by-step instructions.
*   **Responsive Layout:** The interface is designed to provide a seamless experience on both desktop and mobile devices.
*   **Smooth Animations:** Utilizes Framer Motion for elegant page transitions and component animations.
*   **Client-Side Caching:** Implements `localStorage` to cache API results, reducing load times and API usage.

## Technologies Used

*   **Frontend:** React
*   **Routing:** React Router DOM
*   **Styling:** Styled Components
*   **Animations:** Framer Motion
*   **Carousel:** Splide.js for React
*   **Icons:** React Icons

## Getting Started

To run this project locally, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/soumyadeepmandal2003/flavorfusion.git
cd flavorfusion
```

### 2. Set up environment variables

This project uses the [Spoonacular API](https://spoonacular.com/food-api) to fetch recipe data. You will need an API key to run the application.

-   Create a `.env` file in the root of the project.
-   Add your Spoonacular API key to the file:
    ```
    REACT_APP_FOOD_API_KEY=YOUR_API_KEY_HERE
    ```

### 3. Install dependencies

```bash
npm install
```

### 4. Run the development server

```bash
npm start
```

The application will be available at `http://localhost:3000`.

## Project Structure

The project is organized into the following main directories:

```
└── src/
    ├── components/    # Reusable components like carousels, search bar, and category links
    ├── pages/         # Page components for different routes (Home, Cuisines, Recipe, etc.)
    ├── App.js         # Main component containing the layout and routing structure
    ├── index.css      # Global styles
    └── index.js       # Main entry point for the React application


continue this and give me full code/writing as readme file for my project to copy and paste into readme file
