# Recipe-Explorer-Smart-Swapper

🍳 Recipe Explorer + Smart Swapper
📌 Objective
This is a dynamic front-end web application designed to help users manage their recipes, adapt them to dietary needs, and track their cooking journey.

✅ Features
1. 🧾 Recipe Browser
Responsive Card View: Displays recipes with their name, image, short description, and relevant tags.

Filtering: Recipes can be filtered by Category (e.g., Breakfast, Dinner) and Tags (e.g., Vegan, Gluten-Free, Keto, Quick, Healthy).

Search Bar: Allows users to search for recipes by title or ingredient.

2. ➕ Add Your Own Recipe
Comprehensive Form: Users can input:

Recipe Title

Image URL (for visual representation)

Short Description

Ingredients List (one per line)

Instructions

Category (e.g., Breakfast, Lunch, Dinner, Dessert, Snack)

Tags (e.g., gluten-free, keto, comma-separated)

Local Storage Persistence: All added recipes are saved in localStorage, ensuring they persist even after the browser is closed or refreshed.

3. ♻️ Smart Ingredient Swapper
Dietary Adaptability: Integrated directly into the recipe detail view, allowing users to swap ingredients based on selected dietary needs:

Vegan: (e.g., Milk → Almond Milk, Eggs → Flax Eggs)

Gluten-Free: (e.g., Flour → Gluten-Free Flour Blend, Pasta → Gluten-Free Pasta)

Keto: (e.g., Sugar → Erythritol/Stevia, Rice → Cauliflower Rice)

Live Swapping: Displays the swapped version of ingredients instantly within the recipe detail view.

4. ⭐ Favorites & Status Tracking
Favorites List: Users can add or remove recipes from a dedicated "Favorites" list.

"Tried" Status: Recipes can be marked as "Done" after trying them.

UI Indicators: Recipe cards visually indicate if a recipe is:

Favorite ⭐

Tried ✅

5. 📝 Feedback on Tried Recipes
Rating System: Upon marking a recipe as "Done," users are prompted to rate it from 1 to 5 stars.

Text Feedback: Users can also leave a short text comment about their experience.

Display Feedback: Stored feedback (rating and comment) is displayed prominently on that recipe's detail view.

6. ⏱️ Cooking Timer + Checklist
Global Timer: A general-purpose timer allows setting minutes and seconds for any cooking task.

Recipe-Specific Checklist: When viewing a recipe's details, its instructions are converted into an interactive checklist, allowing users to tick off steps as they cook.

🎨 UI Layout
Home Page
Header: Features the application title and navigation buttons (Home, Add Recipe, Favorites).

Controls: Includes a search bar and dropdown filters for categories and tags.

Recipe Grid: A responsive grid displays recipe cards.

Recipe Detail Page (Modal)
Comprehensive View: Opens as a modal over the main content.

Left Panel: Shows the recipe title, large image, description, tags, and action buttons (Favorite, Mark as Done, Edit). Also includes the feedback display.

Right Panel: Contains the Ingredient Swapper, the original/swapped ingredients list, and the instructions presented as a dynamic checklist.

Add Recipe Page (Section)
Input Form: A dedicated section with input fields for all recipe details, styled with Tailwind CSS.

🛠️ Tech Stack Requirements
HTML: HTML5 for semantic structure.

Styling: CSS3, heavily utilizing Tailwind CSS for a modern, responsive design (Flexbox and Grid for layout).

Logic/Data: JavaScript ES6+ for all application logic, DOM manipulation, event handling, and data management.

Persistence: localStorage for client-side data storage (CRUD operations).

Assets: Placeholder images from services like placehold.co are used for recipe images.

📌 Important JavaScript Concepts Used
Arrays & Objects (for recipe data structure)

DOM Manipulation (creating, updating, and removing HTML elements)

Event Listeners (handling user interactions like clicks, input changes, form submissions)

Conditional Rendering (showing/hiding elements based on application state)

Template Literals (for cleaner HTML generation in JavaScript)

localStorage (for persisting data across sessions)

setInterval() (for the cooking timer functionality)

Dynamic Form Handling (processing user input from forms)

🧪 Optional Stretch Goals (Future Enhancements)
Dark Mode Toggle: Implement a switch for a darker UI theme.

Share Recipe URL: Utilize the Web Share API to allow users to share recipe links.

Import/Export: Provide functionality to import or export recipe lists as JSON files.

Accessibility Features: Enhance keyboard navigation and add ARIA labels for improved accessibility.
