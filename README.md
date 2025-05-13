# Flakes - Movie Streaming Website Interface 

flakes.mdkashifali.com

This project is an HTML and CSS-based frontend template for a movie streaming website called "Flakes". It showcases a modern, dark-themed interface with various sections for Browse and discovering movies and series. The design includes a responsive navigation bar, a sidebar for quick actions, featured content sections, and categorized movie lists.

## Features

* **Navigation Bar:**
    * Sticky navbar at the top of the page.
    * Includes a logo, menu items (Home, Movies, Series, Popular, Trends).
    * Profile section with a profile picture, name, and a dropdown icon.
    * Dark/Light mode toggle switch.
* **Sidebar:**
    * Fixed sidebar on the left.
    * Contains icons for Search, Home, Users, Bookmark, Shopping Cart, and Hourglass (possibly for "Watch Later" or "History").
* **Featured Content:**
    * Prominent sections to highlight specific movies or series.
    * Includes a background image, title image/logo, a brief description, and a "WATCH" button.
    * The provided code shows three such featured sections.
* **Movie Lists:**
    * Categorized horizontal scrolling lists for movies/series.
    * Categories include "Trending Now", "Continue Watching for Kashif", "Blockbuster Movies", "Exciting TV Sci-Fi & Fantasy", and "Antiheroes & Outsiders".
    * Each movie item displays a poster.
    * **Hover Effects:** On hovering over a movie item:
        * The poster image scales up and slightly dims.
        * Movie title, a short description, and a "Watch" button appear over the image.
    * Arrow icons for navigating through the movie lists.
* **Dark/Light Mode Toggle:**
    * A toggle switch in the navbar allows users to switch between a dark theme (default) and a light theme.
    * This feature is intended to be implemented with JavaScript (`app.js` is linked but its content is not provided in the prompt). The CSS includes `.active` classes that suggest how the theme change would affect various elements.
* **Footer:**
    * Includes social media icons (Facebook, Instagram, Twitter, YouTube).
    * A list of helpful links (Audio and Subtitles, Help Center, Jobs, Privacy, etc.).
    * Copyright information.
* **Responsive Design:**
    * The CSS includes a media query (`@media only screen and (max-width: 940px)`) that hides the main menu container on smaller screens, suggesting an adaptation for mobile or tablet views.

## Technologies Used

* **HTML5:** For the structure and content of the website.
* **CSS3:** For styling the website, including layout, colors, fonts, and animations/transitions.
* **Google Fonts:** Uses the "Roboto" and "Sen" font families.
* **Font Awesome:** Used for icons throughout the interface.

## File Structure

* `index.html`: The main HTML file containing the structure of the webpage.
* `style.css`: The CSS file containing all the styling rules for the webpage.
* `app.js`: (Linked in HTML) Intended for JavaScript functionalities, particularly the dark/light mode toggle and potentially the movie list carousel. *The actual JavaScript code is not provided in the prompt.*
* `img/`: A directory presumably containing all the images used in the project (profile picture, movie posters, featured content backgrounds, and title images). The specific image paths (e.g., `img/profile.jpg`, `img/f-1.jpg`, `img/1.jpeg`) indicate this structure.

## How to Use

1.  Clone this repository or download the files.
2.  Ensure you have the `img/` directory populated with the necessary image assets as referenced in the HTML (e.g., `profile.jpg`, `f-1.jpg`, `f-t-1.png`, `1.jpeg` through `16.jpg`, etc.).
3.  Open the `index.html` file in a web browser to view the website.

## Potential Future Enhancements (based on the provided code)

* **Implement JavaScript Functionality:**
    * Activate the dark/light mode toggle using `app.js` to add/remove `.active` classes on relevant elements.
    * Implement the movie list carousel functionality using the arrow icons to scroll through movies.
    * Make menu items and sidebar icons interactive (e.g., navigate to different pages or filter content).
* **Backend Integration:** Connect the frontend to a backend system to dynamically load movie data, manage user profiles, and handle streaming.
* **Further Responsiveness:** Enhance the responsive design for a wider range of screen sizes, potentially including a mobile-friendly navigation menu (e.g., a hamburger menu).
* **Accessibility Improvements:** Ensure the website adheres to WCAG guidelines for better accessibility.
