# 🍽️ FlavorFusion


**FlavorFusion** is a dynamic and responsive web application built for food enthusiasts to explore, discover, and enjoy new recipes from around the world.  
Powered by the **Spoonacular API**, it provides an extensive collection of recipes with detailed ingredients, instructions, and curated recommendations.  

---

## 🚀 Features

- **🔍 Recipe Search:** Instantly find recipes using keywords.
- **🌎 Browse by Cuisine:** Explore cuisines such as Italian, American, Thai, Japanese, and more.
- **🎠 Curated Carousels:** Interactive carousels featuring *Random Picks* and *Vegetarian Picks* for inspiration.
- **📜 Detailed Recipe Pages:** View complete recipe details — ingredients, cooking steps, and preparation time.
- **📱 Responsive Layout:** Optimized for both desktop and mobile viewing.
- **✨ Smooth Animations:** Enhanced UX using **Framer Motion** for transitions and animations.
- **⚡ Client-Side Caching:** Implements `localStorage` for faster load times and reduced API usage.

---

## 🛠️ Technologies Used

| Category | Technologies |
|-----------|---------------|
| **Frontend** | React |
| **Routing** | React Router DOM |
| **Styling** | Styled Components |
| **Animations** | Framer Motion |
| **Carousel** | Splide.js (React) |
| **Icons** | React Icons |
| **API** | Spoonacular Food API |

---

## 🧩 Project Structure


The project is organized into the following main directories:

```
FlavorFusion/
├── public/
│ ├── index.html
│ └── favicon.ico
├── src/
│ ├── components/ # Reusable UI components (Carousels, Search Bar, Categories)
│ ├── pages/ # Page components (Home, Cuisine, Recipe)
│ ├── App.js # Main layout and routing logic
│ ├── index.css # Global styles
│ ├── index.js # Application entry point
│ └── utils/ # Helper functions and API utilities
├── .env # Environment variables (API key)
├── package.json
└── README.md
```




---

## ⚙️ Getting Started

Follow these steps to set up **FlavorFusion** locally:

### 1️⃣ Clone the repository
```bash
git clone https://github.com/soumyadeepmandal2003/flavorfusion.git
cd flavorfusion
```

2️⃣ Set up environment variables

This project uses the Spoonacular API
 to fetch recipe data.
You’ll need an API key to run the app.

Create a .env file in the root directory and add your key:
```bash
REACT_APP_FOOD_API_KEY=YOUR_API_KEY_HERE
```

3️⃣ Install dependencies
```bash
npm install
```

4️⃣ Start the development server
```bash
npm start
```

Your app should now be running on 👉 http://localhost:3000


🧠 How It Works

API Integration:
The app fetches recipe data dynamically from the Spoonacular API.

Search Functionality:
Users can search recipes by dish name, cuisine, or ingredient.

Local Caching:
Data fetched once is stored in localStorage to minimize API calls.

Dynamic Routing:
Using React Router DOM for smooth page navigation.

Animation Layer:
Framer Motion enhances transitions and component entry animations.

---

🧰 Available Scripts

In the project directory, you can run:

| Command         | Description                                   |
| --------------- | --------------------------------------------- |
| `npm start`     | Runs the app in development mode              |
| `npm run build` | Builds the app for production                 |
| `npm test`      | Launches the test runner                      |
| `npm run eject` | Exposes configuration files for customization |

---

## 🧑‍💻 Contributions

Contributions are always welcome and appreciated! ❤️  
Whether it’s fixing a bug, improving documentation, or adding a new feature — every contribution helps **FlavorFusion** grow.

If you’d like to contribute, please follow these steps:

---

### 🔧 Steps to Contribute

1. **Fork the Repository**  
   Click on the **Fork** button at the top-right corner of this repository page.  
   This will create your own copy of the project under your GitHub account.

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/<your-username>/flavorfusion.git
   cd flavorfusion
   ```
   
3. **Create a New Branch**
   ```bash
   git checkout -b feature-name
   ```
   
4. **Make Your Changes**
   Edit the files as needed. Make sure your code is clean, well-formatted, and follows best practices.

5. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Added: description of your feature or fix"
   ```

6. **Push to Your Branch**
   ```bash
   git push origin feature-name
   ```

7. **Open a Pull Request (PR)**
   Go to your fork on GitHub.
   Click on Compare & Pull Request.
   Add a clear title and description explaining what you changed and why.
   Submit the pull request for review.

---

## 🧭 Contribution Guidelines

To ensure a smooth collaboration process, please follow these best practices:

- 🧹 **Code Formatting:** Maintain consistent code style, indentation, and naming conventions.  
- 💬 **Commit Messages:** Keep commits **atomic** and write **clear, descriptive** commit messages.  
- 📦 **Dependencies:** If you introduce new dependencies, document them in the `README.md` or add notes in `package.json`.  
- 🧪 **Testing:** Test all features and fixes thoroughly before submitting a Pull Request (PR).  
- 🤝 **Respectful Communication:** Be constructive, respectful, and open to feedback during discussions or reviews.

> “Good code tells a story — make sure yours is readable, meaningful, and easy to follow.” ✨

---

## 🐞 Troubleshooting

If you encounter issues while running or building the app, try the following:

1. 🔑 **Invalid or Missing API Key:**  
   - Ensure your **Spoonacular API key** is correctly set in the `.env` file.  
   - Verify that your key has not reached its daily limit.

2. ⚙️ **Environment Variables Not Working:**  
   - Make sure your `.env` file is placed in the **project root** (not inside `/src`).  
   - Restart your development server after any `.env` change.

3. 🧹 **Cached Data Issues:**  
   - Clear your browser’s `localStorage` and refresh the app to reload new data.

4. 🧱 **Blank Page or Missing Components:**  
   - Double-check all **import paths** and **component names**.  
   - Ensure that the **React Router** setup in `App.js` matches your folder structure.

5. 🪄 **Build or Dependency Errors:**  
   - Delete the `node_modules` folder and reinstall dependencies:  
     ```bash
     rm -rf node_modules
     npm install
     ```  
   - Then restart your app with:  
     ```bash
     npm start
     ```

---

> 💡 **Tip:**  
> If the issue persists, open a [GitHub Issue](https://github.com/soumyadeepmandal2003/flavorfusion/issues) describing your problem.  
> Include screenshots, console logs, and steps to reproduce it — this helps maintainers assist you faster.

---

## 🌟 Acknowledgements

- [**Spoonacular API**](https://spoonacular.com/food-api) — for providing recipe data  
- [**React**](https://reactjs.org/) — for the frontend UI framework  
- [**Framer Motion**](https://www.framer.com/motion/) — for smooth animations and transitions  
- [**Splide.js**](https://splidejs.com/) — for interactive carousel components  

---

## 💡 Author

**👨‍💻 Soumyadeep Mandal**  
[GitHub](https://github.com/soumyadeepmandal2003) • [LinkedIn](https://www.linkedin.com/in/soumyadeep2003/)  

> *“Ignite Flavor, Elevate Every Bite.”* 🍲
