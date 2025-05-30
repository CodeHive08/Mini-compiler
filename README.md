# 💻 Mini Compiler
A **Mini Compiler** web application built using HTML, CSS, JavaScript, Node.js, and CompileX that lets you write, compile, and execute code for **C++**, **Java**, and **Python**. The interface features syntax highlighting powered by **CodeMirror**.

## ✨ Features

- 🖊️ Syntax-highlighted code editor using CodeMirror
- ⚙️ Compile & execute C++, Java, and Python code
- 📥 Accepts custom input during code execution
- 💡 Output/error is displayed in real-time
- 🌐 Responsive UI with Bootstrap 5

---

## 🛠️ Technologies Used

| Tech         | Purpose                              |
|--------------|--------------------------------------|
| HTML/CSS     | Structure and styling of the UI      |
| JavaScript   | Client-side logic and interaction    |
| Node.js      | Backend server to run code           |
| CompileX     | Node library to compile/run code     |
| CodeMirror   | Syntax-highlighting code editor      |
| Bootstrap    | Responsive design and layout         |

---

## 📁 Project Structure

mini-compiler/
│
├── api.js # Express server logic (backend)
├── index.html # Frontend UI
├── /codemirror # Local CodeMirror library files
├── package.json # Node dependencies
└── README.md # Project documentation


## 🧑‍💻 Author

**Sandeep Singh Mehta**

---

## 🚀 Getting Started

### 1. Clone the Repository
git clone https://github.com/CodeHive08/Mini-compiler.git
cd mini-compiler
### 2. Install Node.js and Dependencies
Ensure you have Node.js installed. Then run:
npm install
This will install compilex and other required packages.

### 3. Set Up CodeMirror
You can set up CodeMirror either from a CDN or locally (already included in your project).

✅ Option A: Use Pre-included Local CodeMirror
CodeMirror is already included in the codemirror/ directory and referenced in index.html:

<html>
<link rel="stylesheet" href="codemirror/codemirror-5.65.19/lib/codemirror.css">
<script src="codemirror/codemirror-5.65.19/lib/codemirror.js"></script>
Make sure your folder structure is intact as per the repo.

🌐 Option B: Use CDN (if you prefer this instead)
<html>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/codemirror/5.65.19/codemirror.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/codemirror/5.65.19/codemirror.min.js"></script>
⚠️ Remove the /codemirror static path from api.js if using CDN.

### 4. Run the Server
node api.js
Server will start on:
http://localhost:8000
Open this in your browser to access the compiler.

### 🧪 Supported Languages
✅ C++ (g++)

✅ Java

✅ Python

Custom input is supported for all three languages.

### 📸 UI Preview
![image](https://github.com/user-attachments/assets/ca960117-6ebc-4e34-8919-3c989e43db2f)


### 🛡️ Notes
Requires internet access for Bootstrap & CodeMirror CDN (unless using local files).

Be cautious when running untrusted code — this is not production-safe.

Works best on modern browsers (Chrome, Edge, Firefox).

### ⭐ Contributing
Pull requests are welcome! For major changes, please open an issue first.

### 📜 License
This project is licensed under the MIT License.
Let me know if you'd like me to generate:
- Badges (Node version, license, etc.)
- A license file
- A `.gitignore` file
- Deployment instructions (e.g., using `render`, `vercel`, or `replit`)

I'll be happy to help!






