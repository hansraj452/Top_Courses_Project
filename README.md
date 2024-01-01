 **# Top_Courses_Project**
![image](https://github.com/hansraj452/Top_Courses_Project/assets/96901841/60c85b34-49e2-4146-9c20-1707226def8d)
![image](https://github.com/hansraj452/Top_Courses_Project/assets/96901841/2004339d-9fc7-4185-8267-70734c8ad1ee)
![image](https://github.com/hansraj452/Top_Courses_Project/assets/96901841/296d5476-b231-43ef-acfe-b33877b97dfc)


**## Overview**

This project is a simple React application that displays a list of top courses, without any backend integration.

**## File Structure**

```
Top_Courses_Project/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── components/
│   │   ├── Card.js
│   │   ├── Cards.js
│   │   ├── Filter.js
│   │   └── Navbar.js
│   ├── index.css
│   ├── index.js
│   ├── App.js
│   ├── data.js
│   ├── Spinner.css
│   └── Spinner.js
├── .gitignore
├── package-lock.json
├── package.json
└── tailwind.config.js
```

**## Key Files**

- **index.js:** The entry point of the React application.
- **App.js:** The main component that renders the entire application.
- **data.js:** Contains the data for the top courses (likely in a hardcoded format).
- **components/:** Contains reusable UI components:
    - **Card.js:** Renders an individual course card.
    - **Cards.js:** Renders a list of course cards.
    - **Filter.js:** Provides functionality to filter courses (if applicable).
    - **Navbar.js:** Renders the navigation bar.
- **Spinner.js:** Displays a loading spinner while data is being fetched (if applicable).

**## Setup**

1. Clone this repository:
   ```bash
   git clone https://github.com/hansraj452/Top_Courses_Project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Top_Courses_Project
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

**## Running the Project**

1. Start the development server:
   ```bash
   npm start
   ```
2. Open http://localhost:3000 in your browser to view the application.

**## Additional Notes**

- This project utilizes Tailwind CSS for styling.
- Consider adding brief descriptions of the data structure in `data.js`
-## Data Handling
data.js: This file manages the course data and filtering options:
filterData: An array of objects defining available filters for courses, including "All", "Development", "Business", "Design", and "Lifestyle".
apiUrl: A URL pointing to a third-party API that presumably provides the course data (although the application doesn't currently fetch data from this URL).
## Potential Data Fetching

While the application currently doesn't fetch data from the API, the presence of apiUrl suggests that it might be intended for future implementation.
## Filtering Functionality
The Filter.js component likely uses the filterData to provide users with the ability to filter courses based on categories selected by the user.



