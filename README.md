
# Student Information Dashboard

A responsive, interactive web application built using HTML5, CSS3, JavaScript, Bootstrap 5, and the DummyJSON REST API. The dashboard displays user information in a table and allows users to filter and search records dynamically.

## Live Demo

🚀 **[View Student Information Dashboard](https://student-info-dashboard.vercel.app/)**

## Features

- **Dynamic Student Table:** Displays user IDs, names, and genders in a structured table.
- **Show All Records:** Displays all available records.
- **Gender Filtering:** Filter records by male or female gender.
- **Real-Time Search:** Search users by name as you type.
- **REST API Integration:** Fetch user data from the DummyJSON API.
- **Asynchronous JavaScript:** Uses `async/await` and `fetch()` to retrieve data.
- **Responsive Styling:** Uses Bootstrap 5 components and table styles.
- **Initial Data Display:** Shows sample records before API data loads successfully.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5.3.3
- DOM Manipulation
- Arrays and Objects
- Array Methods: `map()`, `filter()`, and `includes()`
- String Methods: `toLowerCase()`
- Fetch API and REST API Integration
- Asynchronous JavaScript: `async/await`
- JSON Data Handling
- Google Fonts — Poppins
- Vercel for Deployment

## API Used

**DummyJSON Users API**

https://dummyjson.com/users

The application fetches user records from the API and maps the returned data into objects containing an ID, full name, and gender.

## How It Works

1. The application initially displays sample student records.
2. JavaScript fetches user data from the DummyJSON API.
3. The response is converted into JSON.
4. The application extracts each user's ID, first name, last name, and gender.
5. The table updates dynamically with the retrieved data.
6. Users can filter the table by gender or search by name.

## Getting Started

### Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/k-siddhartha-ai/student-information-dashboard.git
   ```

2. Open the downloaded repository folder.
3. Open `student_info_dashboard/index.html` in your browser.
4. Ensure you have an internet connection so Bootstrap, Google Fonts, and the DummyJSON API can load.

No additional package installation is required.

## Project Structure

```text
student-information-dashboard/
├── README.md
└── student_info_dashboard/
    └── index.html
```

## What I Learned

- Manipulating HTML elements using the DOM
- Rendering table rows dynamically using JavaScript
- Filtering and searching data with array methods
- Handling API responses using `fetch()` and `async/await`
- Working with JSON data and JavaScript objects
- Building interfaces using Bootstrap 5
- Deploying and documenting a web application

## Future Improvements

- Add pagination for large datasets.
- Add sorting by ID and name.
- Improve error messages when the API is unavailable.
- Add loading indicators while fetching data.
- Improve mobile table navigation.
- Add more advanced search and filtering options.

## Author

**Karne Siddhartha**

- GitHub: https://github.com/k-siddhartha-ai
- LinkedIn: https://www.linkedin.com/in/karne-siddhartha-163bb1369/

---

Feedback and suggestions are welcome!
