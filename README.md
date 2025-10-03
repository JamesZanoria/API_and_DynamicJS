API and Dynamic JavaScript Project

Overview

This project demonstrates the use of JavaScript Fetch API to dynamically load and display data from external APIs. The website follows a given Figma prototype for structure and design. It consists of multiple pages and provides navigation between a Friends page and the main Facebook page.

----------------------------------------------------------------------------------

Features

- Responsive layout based on the provided Figma prototype.
- Fetches and displays data dynamically from APIs (no hardcoding).
- Navigation between pages:

  - Clicking Friends loads the Friends page.
  - Clicking Facebook on the Friends page redirects back to the homepage.
- Scrollable pages for better usability.
- Clean and structured HTML, CSS, and JavaScript implementation.

----------------------------------------------------------------------------------

APIs Used

1. Users API

   - Endpoint: [https://jsonplaceholder.typicode.com/users](https://jsonplaceholder.typicode.com/users)
   - Used to fetch and display a list of users (friends).

2. Products API

   - Endpoint: [https://mdn.github.io/learning-area/javascript/apis/fetching-data/can-store/products.json](https://mdn.github.io/learning-area/javascript/apis/fetching-data/can-store/products.json)
   - Used to display product data dynamically.

----------------------------------------------------------------------------------

Implementation Details

1. Dynamic Data Loading

   - Data is retrieved using `fetch()` and rendered in the DOM.
   - No hardcoded data; all displayed content comes directly from APIs.

2. Navigation

   - A navigation bar is included.
   - "Friends" button → navigates to the Friends page.
   - "Facebook" button on Friends page → redirects back to `index.html`.

3. Design and Layout

   - Matches the Figma prototype as closely as possible.
   - Scrollable layout for better accessibility.

----------------------------------------------------------------------------------

Scope and Limitations

- Implemented with HTML, CSS, and Vanilla JavaScript only.
- Limited to the data provided by the given APIs.
- Backend/server-side logic is not included.
