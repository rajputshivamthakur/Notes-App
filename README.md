## 📝 Project Title – Notes App

A minimal and intuitive Notes application built with **ReactJS**, allowing users to create, delete, and persist notes using **Local Storage**. Designed for a clean user experience and functional reliability.

---

### 🔧 Tech Stack

* **Frontend:** ReactJS, JavaScript (ES6+), HTML5, CSS3
* **Storage:** Local Storage API
* **Testing Tools:** Jest, React Testing Library, Browser DevTools
* **Version Control:** Git, GitHub

---

### 📋 Features

* Add, edit, and delete notes.
* Persistent storage using browser's Local Storage.
* Responsive layout for desktop and mobile.
* Real-time character count and input validation.

---

### ✅ Testing Details

* 🔹 **Unit Testing:** Basic tests written using **Jest** to verify functionality of note creation and deletion.
* 🔹 **Component Testing:** Used **React Testing Library** to simulate user actions like typing, deleting, and form submission.
* 🔹 **Manual Testing:** Covered edge cases such as:

  * Adding an empty note
  * Exceeding character limits
  * Refreshing the page to test Local Storage persistence
* 🔹 **Debugging & Validation:** Leveraged **browser DevTools** to inspect DOM changes, check storage behavior, and validate UI responsiveness.

---

### ⚙️ Installation & Setup

1. Clone the repository
   `git clone https://github.com/rajputshivamthakur/Notes-App.git`

2. Navigate into the project directory
   `cd notes-app`

3. Install dependencies
   `npm install`

4. Start the development server
   `npm start`

---

### 📂 Folder Structure

```
/src
 ┣ /components
 ┃ ┗ NoteCard.js
 ┣ /tests
 ┃ ┗ NoteCard.test.js
 ┣ App.js
 ┗ index.js
```

---

### 🧪 Test Commands

```bash
# Run all test cases
npm test
```

---

### 🧠 Learnings & Takeaways

* Developed reusable and testable UI components.
* Strengthened understanding of **manual testing principles** and edge-case handling.
* Gained hands-on experience with **React Testing Library** and basic **unit testing**.

---

### 📌 Future Improvements

* Add tagging and search/filter features.
* Implement E2E testing with Playwright or Cypress.
* Integrate basic CI workflow with GitHub Actions.

---

### 🙌 Acknowledgements

* ReactJS Official Docs
* Testing Library Docs
* YouTube tutorials by Web Dev Simplified

