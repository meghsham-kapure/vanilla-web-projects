# vanilla-web-projects
A collection of beginner to advanced HTML, CSS, and JavaScript projects built while practicing core web development concepts. This repo is my personal playground and learning log—covering DOM manipulation, event handling, arrays &amp; objects, APIs, localStorage, and more

# JavaScript Projects  Beginner to Advanced

##  Beginner Level – DOM + Core JS

### 1. Digital Clock / Countdown Timer

**Requirements:**

- Display current time (hours, minutes, seconds).
    
- Update every second using `setInterval`.
    
- Countdown timer: input a future date/time → display remaining days, hours, minutes, seconds.
    
- Buttons: start, stop, reset.
    

**Bonus:** Add themes (dark/light mode).



### 2. Quiz App

**Requirements:**

- Store questions/answers in an array of objects.
    
- Show one question at a time with multiple-choice answers.
    
- Track score, show correct/wrong instantly.
    
- At the end → display result with restart option.
    

**Bonus:** Add timer for each question.



### 3. Price Calculator (Array Map/Reduce)

**Requirements:**

- Store products in an array: `{name, price}`.
    
- Use `map` to display them in a list/table.
    
- Use `reduce` to calculate total price.
    
- Add discount calculation (e.g. 10% off).
    

**Bonus:** Allow user to add/remove items dynamically.



### 4. Dynamic Student Report Card (Objects + DOM Creation)

**Requirements:**

- Create student object `{ name, rollNo, marks: {math, science, english} }`.
    
- Dynamically generate a table/card showing marks.
    
- Use `Object.keys`/`Object.values` to calculate total & average.
    
- Display grade (A/B/C) based on average.
    

**Bonus:** Support multiple students in an array.



### 5. To-Do App (with Local Storage)

**Requirements:**

- Add, edit, delete tasks.
    
- Mark tasks as completed (strike-through).
    
- Save tasks in `localStorage` so they persist after refresh.
    

**Bonus:** Add categories (Work, Personal).





##  Intermediate Level – APIs + Async

### 6. Weather App (API)

**Requirements:**

- Input city name, fetch weather data (OpenWeather API).
    
- Display temperature, humidity, description, and weather icon.
    
- Handle errors (e.g., invalid city).
    

**Bonus:** Show 5-day forecast.



### 7. Movie Search App (API + Debounce)

**Requirements:**

- Search movies using OMDb API.
    
- Use debounce to avoid too many requests while typing.
    
- Show movie poster, title, year.
    
- On click → show more details.
    

**Bonus:** Add pagination for results.



### 8. Expense Tracker

**Requirements:**

- Add income and expense transactions.
    
- Show balance = income - expense.
    
- Save data in localStorage.
    
- Visualize data using Chart.js (pie chart for expenses).
    

**Bonus:** Export data as CSV/JSON.





##  Advanced Level – State & Architecture

### 9. Recipe Finder App

**Requirements:**

- Search recipes from MealDB API.
    
- Show recipe image, name, and ingredients.
    
- Add favorite recipes (store in localStorage).
    

**Bonus:** Offline mode (show last searched recipes).



### 10. E-Commerce Product Page

**Requirements:**

- Display products from JSON or API.
    
- Implement filters (category, price range).
    
- Add to cart (store in localStorage).
    
- Cart page with quantity update & remove.
    

**Bonus:** Checkout simulation with form validation.



### 11. Chat App (Realtime)

**Requirements:**

- Use Firebase Realtime DB or WebSockets.
    
- Allow user to enter name and send messages.
    
- Display messages instantly for all users.
    
- Show timestamp for each message.
    

**Bonus:** Add “user is typing…” feature.



### 12. Full Blog Platform (Mini CMS)

**Requirements:**

- Create, edit, delete blog posts.
    
- Store data in JSON server or Firebase.
    
- Simple login (fake authentication).
    
- Routing: Home (all posts), Single Post, New Post.
    

**Bonus:** Add image upload support.



