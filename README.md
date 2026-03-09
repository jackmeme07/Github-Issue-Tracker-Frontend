# GitHub Issues Tracker

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![DaisyUI](https://img.shields.io/badge/DaisyUI-5A0FC8?style=for-the-badge&logo=daisyui&logoColor=white)

A responsive web application for tracking and managing GitHub issues. Built with vanilla JavaScript, it provides an intuitive interface to view, filter, and search issues fetched from a REST API.

## 🌟 Features

- **Secure Login**: User authentication with default admin credentials
- **Issue Management**: View all issues in a clean card-based layout
- **Filtering**: Filter issues by status (All, Open, Closed)
- **Search Functionality**: Search issues by keywords
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Interactive UI**: Hover effects, active states, and smooth transitions
- **Modal Details**: Click on issue titles to view detailed information (planned feature)
- **Loading States**: Spinner during data fetching
- **Status Indicators**: Visual borders and icons based on issue status

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS, DaisyUI
- **Icons**: Font Awesome
- **Fonts**: Geist (Google Fonts)
- **API**: RESTful API for issue data

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/jackmeme07/Github-Issue-Tracker-Frontend.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd github-issues-tracker
   ```

3. **Open in browser**:
   - Open `index.html` in your preferred web browser
   - No additional setup required as it uses CDN links for dependencies

## 🚀 Usage

1. **Login**:
   - Open `index.html`
   - Enter the demo credentials:
     - Username: `admin`
     - Password: `admin123`

2. **Browse Issues**:
   - View all issues on the main page
   - Use tabs to filter by status (All, Open, Closed)
   - Use the search bar to find specific issues

3. **View Details**:
   - Click on issue titles to open detailed modals (feature in development)

## 🔗 API Endpoints

The application fetches data from the following API endpoints:

- **All Issues**: `https://phi-lab-server.vercel.app/api/v1/lab/issues`
- **Single Issue**: `https://phi-lab-server.vercel.app/api/v1/lab/issue/{id}`
  - Example: `https://phi-lab-server.vercel.app/api/v1/lab/issue/33`
- **Search Issues**: `https://phi-lab-server.vercel.app/api/v1/lab/issues/search?q={searchText}`
  - Example: `https://phi-lab-server.vercel.app/api/v1/lab/issues/search?q=notifications`

## 📱 Screenshots

*Design mockups available in `GitHub Issues Tracker.fig` (Figma file)*

## 📋 JavaScript Concepts Explained

### 1. Difference between `var`, `let`, and `const`

- **`var`**: Function-scoped variable declaration. Can be redeclared and updated. Hoisted to the top of its scope.
- **`let`**: Block-scoped variable declaration. Can be updated but not redeclared in the same scope. Not hoisted.
- **`const`**: Block-scoped constant declaration. Cannot be updated or redeclared. Must be initialized at declaration. Not hoisted.

### 2. Spread Operator (`...`)

The spread operator allows an iterable (like an array or object) to be expanded in places where zero or more arguments or elements are expected. It's used for:
- Copying arrays/objects
- Merging arrays/objects
- Passing array elements as function arguments
- Converting iterables to arrays

### 3. Difference between `map()`, `filter()`, and `forEach()`

- **`map()`**: Creates a new array by applying a function to each element of the original array. Returns a new array of the same length.
- **`filter()`**: Creates a new array with all elements that pass a test implemented by the provided function. Returns a subset of the original array.
- **`forEach()`**: Executes a provided function once for each array element. Doesn't return anything (undefined). Used for side effects.

### 4. Arrow Function

Arrow functions are a concise syntax for writing function expressions. They:
- Use `=>` syntax
- Don't have their own `this` binding (inherit from parent scope)
- Are anonymous by default
- Have implicit return for single expressions
- Cannot be used as constructors

### 5. Template Literals

Template literals are string literals that allow embedded expressions. They:
- Use backticks (`` ` ``) instead of quotes
- Allow multi-line strings
- Support string interpolation with `${expression}`
- Can contain placeholders for variables or expressions
- Preserve whitespace and newlines

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- **GitHub Repository**: https://github.com/jackmeme07/Github-Issue-Tracker-Frontend
- **Live Demo**: https://jackmeme07.github.io/Github-Issue-Tracker-Frontend/

---

*This project was created as part of an assignment for learning web development concepts.*


