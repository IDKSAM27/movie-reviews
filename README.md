# 🎥 MOV SITE: Discover Your Next Favorite Movie!

Welcome to **MOV SITE**, your one-stop destination to explore and discover amazing movies. Powered by **The Movie Database (TMDb)** API, this site allows you to browse popular movies or search for your favorites with ease. 🌟

---

## 🚀 Features

- **Dynamic Movie Gallery:** Automatically fetches and displays the most popular movies.
- **Search Functionality:** Find movies by title using a clean and intuitive search bar.
- **Stylish Design:** A sleek, dark-themed UI for an immersive experience.
- **Responsive Layout:** Enjoy a seamless experience on desktop, tablet, or mobile.

---

## 📸 Screenshots

### Home Page
![Home Page Preview](https://via.placeholder.com/800x400?text=Add+Screenshot+Here)

### Search Results
![Search Results Preview](https://via.placeholder.com/800x400?text=Add+Screenshot+Here)

---

## 🛠️ Technologies Used

- **HTML5**: For structuring the content.
- **CSS3**: For styling and creating a visually appealing layout.
- **JavaScript**: To handle the dynamic content and API calls.
- **The Movie Database (TMDb) API**: To fetch data for movies.

---

## 🌟 How It Works

1. **Fetch Popular Movies:** On loading the site, the most popular movies are fetched and displayed.
2. **Search Movies:** Type a movie name into the search bar and hit "Enter" to find what you're looking for.
3. **Dynamic Updates:** The movie gallery updates instantly with your search results.

---

## 🖥️ Setup Instructions

### Prerequisites
- A modern web browser.
- A code editor (e.g., VS Code) for local development.
- An API key from [TMDb](https://www.themoviedb.org/documentation/api).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mov-site.git
2. Navigate to the project directory:
   ```bash
   cd mov-site
3. Open script.js and replace the placeholder API key with your own:
   ```javascript
   const APILINK = 'https://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&api_key=YOUR_API_KEY&page=1';
4. Open index.html in your browser to view the project.

---

## 📁 File Structure
  ```graphql
  mov-site/
  ├── index.html      # Main HTML file
  ├── style.css       # Stylesheet for the UI
  ├── script.js       # JavaScript file for API interaction
  └── README.md       # Project documentation
```
## 🛠️ Future Enhancements
- Add filters for genres, release dates, and ratings.
- Include a "Load More" button for pagination.
- Implement a detailed movie page with description and trailers.

---

## 🙌 Acknowledgments
- **TMDIb API:** For providing a robust database of movies.
- **You:** For exploring my repo's and this project.

