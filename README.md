# MixMaster

MixMaster is an interactive web application that fetches cocktail recipes from the Cocktail DB API. It is designed to help you discover enchanting drink recipes and take your mixology game to the next level. Whether you're hosting a party or just looking for a refreshing drink, MixMaster has you covered!

## Live Demo

You can access the live app here: [MixMaster](https://mixmaster-cocktails-app.netlify.app/)

## Features

- **Search for Cocktails:** Find your favorite cocktails or explore new ones using the search functionality.
- **Detailed Cocktail Information:** Get detailed information about a selected cocktail, including ingredients, preparation instructions, and more.
- **Newsletter Subscription:** Stay updated with the latest cocktail recipes and trends by subscribing to the newsletter.
- **Responsive Design:** Optimized for various screen sizes, making it accessible on desktops, tablets, and mobile devices.
- **Error Handling:** User-friendly error pages for a smooth browsing experience.
- **React Query Integration:** Efficient data fetching and caching for a seamless user experience.

## Technologies Used

- **Frontend:** React.js with React Router
- **State Management:** React Query
- **Styling:** Styled-components
- **Notifications:** react-toastify
- **API:** [TheCocktailDB API](https://www.thecocktaildb.com/)
- **Development Tools:** React Query Devtools

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd mixmaster
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:3000`.

## Folder Structure

```
├── src
│   ├── components       # Reusable UI components
│   ├── pages            # Application pages
│   ├── assets           # Static assets and styles
│   ├── main.jsx         # Entry point
│   └── App.jsx          # Main application logic
└── README.md            # Project documentation
```

## Key Files

- `main.jsx`: Sets up ReactDOM and includes the ToastContainer.
- `App.jsx`: Configures routing, React Query, and the application layout.
- `Landing.jsx`: Displays a list of cocktails and a search form.
- `Cocktail.jsx`: Displays detailed information about a specific cocktail.
- `Newsletter.jsx`: Handles newsletter subscription with form submission.
- `Error.jsx` & `SinglePageError.jsx`: Custom error components for graceful error handling.

## Usage

1. **Search for Cocktails:**

   - Use the search bar on the homepage to find cocktails by name.
   - Click on a cocktail to view its details.

2. **Subscribe to Newsletter:**

   - Navigate to the Newsletter page.
   - Fill in the required fields and submit the form.

3. **Explore the About Page:**
   - Learn more about MixMaster and its purpose.

## API Reference

MixMaster uses the [TheCocktailDB API](https://www.thecocktaildb.com/) to fetch cocktail data. Below are the key endpoints utilized:

- **Search Cocktails by Name:**
  `https://www.thecocktaildb.com/api/json/v1/1/search.php?s=<name>`

- **Get Cocktail Details by ID:**
  `https://www.thecocktaildb.com/api/json/v1/1/lookup.php?i=<id>`

---

Enjoy using MixMaster and discover your next favorite drink!
