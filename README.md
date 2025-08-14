# Fetch and Display User Data using JavaScript Fetch API

## 📌 Project Overview
This project demonstrates how to use the **JavaScript Fetch API** to retrieve user data from a public API and display it on a webpage. It includes proper error handling, styling, and a reload button to refetch the data.

**Public API Used:**  
[https://jsonplaceholder.typicode.com/users](https://jsonplaceholder.typicode.com/users)

---

## 📂 Project Structure
fetch-api-project/
│
├── index.html # Main HTML file
├── css/
│ └── style.css # Styling for the webpage
└── js/
└── script.js # JavaScript logic for fetching and displaying data

yaml
Copy
Edit

---

## ⚙️ Features
- Fetches user data from a public API.
- Displays **name, email, and address** for each user.
- Reload button to refetch data without refreshing the page.
- Error handling for network and HTTP errors.
- Styled cards for better UI.

---

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/fetch-api-project.git
Open the project folder:

bash
Copy
Edit
cd fetch-api-project
Run the project:

Open index.html in your browser.

📸 Screenshot
(Add a screenshot of your webpage here after running it)

🔍 How It Works
The fetchUsers() function uses fetch() to make a GET request to the API.

If the request is successful, displayUsers() loops through the JSON response and creates user cards dynamically.

If there is an error (network or HTTP), it shows an error message.

The "Reload Data" button calls fetchUsers() again to update the displayed list.

📚 Learning Outcomes
Using Fetch API in JavaScript.

Working with async/await for asynchronous operations.

Parsing and using JSON data.

Handling errors using try...catch.

DOM manipulation to create and update elements dynamically.

Styling layouts with CSS.

