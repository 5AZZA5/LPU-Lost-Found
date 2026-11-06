# 🎒 LPU Lost & Found

A campus-oriented Lost & Found web application designed to help Lovely Professional University (LPU) students report lost belongings, post items they have found, and browse reports to help reunite items with their owners.

🔗 **Live Demo:** [LPU Lost & Found](https://nimble-croissant-128388.netlify.app/)

---

## ✨ Features

- **Report an Item:** Choose whether you have lost or found something and submit its details.
- **Detailed Reports:** Include item name, category, location, date, description, and contact information.
- **Categories:** Electronics, Books and Notes, Clothing, Accessories, and Other.
- **Browse Reports:** View reported items through organized cards.
- **Filter Reports:** Display all reports, lost items only, or found items only.
- **Browser Storage:** Reports are saved using `localStorage` and remain available after refreshing the page in the same browser.
- **Safe Rendering:** User-submitted text is rendered using `textContent`, helping prevent HTML injection.
- **Responsive Design:** Interface adapts to desktop and mobile screen sizes.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure, content, and report forms |
| CSS3 | Styling, layout, and responsive design |
| JavaScript (Vanilla) | Form handling, filtering, dynamic content, and storage |
| LocalStorage | Browser-based report persistence |
| Netlify | Website hosting and deployment |

---

## 📁 Project Structure

```text
LPU-Lost-Found/
├── index.html    # Page layout, report form, and items section
├── style.css     # Styling and responsive design
├── script.js     # Form handling, storage, and filtering
└── README.md     # Project documentation
```

---

## 🚀 Getting Started

No installation or build step is required.

1. Clone the repository:

   ```bash
   git clone https://github.com/5AZZA5/LPU-Lost-Found.git
   ```

2. Open the project folder:

   ```bash
   cd LPU-Lost-Found
   ```

3. Open `index.html` in your web browser.

---

## 📖 How to Use

1. Open the website.
2. Navigate to **Report an Item**.
3. Select whether you have lost or found an item.
4. Enter the item name, category, location, date, description, and contact details.
5. Click **Submit Report**.
6. Browse the reported items section to view your report.
7. Use the filters to switch between lost and found items.

---

## ⚠️ Limitations

This application currently uses browser-based `localStorage` for data storage.

- Reports are stored locally in the browser.
- Reports are not automatically shared between different users or devices.
- Clearing browser storage may remove saved reports.
- The application does not currently provide authentication or ownership verification.

A backend server and database would be required to support a shared campus-wide Lost & Found system.

---

## 🔮 Future Improvements

- Backend API and database integration.
- User authentication and account management.
- Item image uploads.
- Search and sorting functionality.
- Edit, delete, and resolve report options.
- Item ownership verification workflow.
- Administrative dashboard.
- Notifications when matching lost and found items are reported.

---

## 👨‍💻 Project

**LPU Lost & Found**

GitHub: [@5AZZA5](https://github.com/5AZZA5)

---

⭐ If you find this project useful, consider giving it a star!