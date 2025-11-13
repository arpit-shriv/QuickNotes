# 📝 QuickNotes – React + Tailwind Note Taking App

[![GitHub stars](https://img.shields.io/github/stars/arpit-shriv/React-js?style=social)](https://github.com/arpit-shriv/React-js/stargazers)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18+-61DAFB?logo=react&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3+-38B2AC?logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-4+-646CFF?logo=vite&logoColor=white)

A simple and clean notes-taking application built with **React** and **TailwindCSS**.  
You can add notes, view them instantly, and delete them whenever needed.  
Perfect for beginners learning React state management!

---

## 📸 Screenshot

![App Screenshot](https://github.com/user-attachments/assets/4bba98f1-0150-4511-88f4-e205dea09ddf)


## ✨ Features

- ➕ Add notes with title and details  
- 📌 Notes appear instantly in the Recent Notes panel  
- 📜 Scrollable note text (delete button stays fixed)  
- 🧩 Sticky-note card UI  
- 🗑️ Delete notes individually  
- ⚡ Live updates using React’s useState  
- 🎨 Styled completely with Tailwind CSS  

---

## 🛠️ Tech Stack

| Technology          | Purpose           |
|---------------------|-------------------|
| **React JS**        | Frontend library  |
| **Vite**            | Fast dev bundler  |
| **Tailwind CSS**    | Styling           |
| **JavaScript (ES6+)** | Logic           |

---

## 📂 Project Structure

```
/public
  ├─ screenshot.png
  ├─ demo.gif
/src
  ├─ App.jsx
  ├─ main.jsx
  └─ index.css
package.json
tailwind.config.js
README.md
```
---

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/arpit-shriv/QuickNotes.git
cd QuickNotes
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Start the Development Server
```bash
npm run dev
```
Now open the shown localhost URL in your browser.

## 🧠 How It Works

### 🟦 Adding a Note
- User enters the note title & details  
- On submit → note is added to `task` state array  
- UI updates automatically  

---

### 🟥 Deleting a Note
- Each note has a delete button  
- Clicking deletes the note from state via `splice()`  
- React updates instantly  

---

### 🧾 Scrollable Notes
- Long text scrolls using `overflow-y-auto`  
- Delete button stays fixed at the bottom  

---

## 🚀 Future Enhancements

- LocalStorage saving  
- Edit note functionality  
- Search feature  
- Dark/light theme  
- Drag & drop notes layout  
- Add animations  

---

## ☁️ Deployment

### ▶️ Deploy on Vercel
1. Go to **https://vercel.com**  
2. Import your GitHub repository  
3. Build command → `npm run build`  
4. Output directory → `dist`  
5. Deploy 🎉  

---

### ▶️ Deploy on Netlify
1. Go to **https://netlify.com**  
2. Import GitHub repository  
3. Build command → `npm run build`  
4. Publish directory → `dist`  
5. Deploy 🎉  

---

## 🤝 Contributing

Pull requests are welcome!  
For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the **MIT License**.

---
