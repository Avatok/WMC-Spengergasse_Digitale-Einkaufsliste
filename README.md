# 🛒 Digital Shopping List

A simple, responsive **digital shopping list** built as a web development project at **HTL Spengergasse**. Add products, track what you've already bought, and keep an eye on the remaining cost of your shopping.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?logo=bootstrap&logoColor=white)

## ✨ Features

- **Add products:** Enter an item name, quantity, and unit price.
- **Manage your list:** Mark items as purchased (or undo that action) and delete items you no longer need.
- **Automatic total:** See the combined cost of **unpurchased items**, calculated as quantity × unit price.
- **Persistent browser storage:** Items and their purchased status are saved using `localStorage`, so they remain available after refreshing the page in the same browser.
- **Responsive layout:** Bootstrap-based interface for mobile, tablet, and desktop screens.
- **Input validation:** Check for missing or invalid values and display an error modal.

## 🛠️ Tech Stack

| Technology | Purpose |
| --- | --- |
| HTML5 | Page structure and form inputs |
| CSS3 | Custom styling |
| JavaScript (Vanilla JS) | Shopping list logic, DOM updates, and storage |
| Bootstrap 5.1.3 | Responsive layout, buttons, and modal |
| Font Awesome 5 | Icons |
| jQuery | Modal-related script |

## 🚀 Getting Started

No installation, build step, or backend is required.

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/WMC-Spengergasse_Digitale-Einkaufsliste.git
   ```

2. Open the project folder:

   ```bash
   cd WMC-Spengergasse_Digitale-Einkaufsliste
   ```

3. Open **`index.html`** in a browser. Alternatively, serve the folder with a local development server such as VS Code Live Server.

> **Note:** An internet connection is needed to load Bootstrap, Font Awesome, and jQuery from their CDNs. Replace `YOUR_USERNAME` with your GitHub username in the clone URL.

## 📖 How to Use

1. Enter the **quantity**, **product name**, and **unit price**.
2. Click **Hinzufügen** (Add) to create an entry.
3. Click **Durchstreichen** to mark an item as purchased; click **Nicht Durchstreichen** to undo it.
4. Click **Löschen** to remove an item.
5. Check **Gesamt** for the total price of items you still need to buy.

## 📁 Project Structure

```text
WMC-Spengergasse_Digitale-Einkaufsliste/
├── index.html          # Main page and UI
├── CSS/
│   └── Styles.css      # Custom styling
├── JS/
│   ├── Index.js        # Item management, totals, localStorage
│   └── Modal.js        # Input validation and error modal
└── Grafiken/
    └── Icon.png        # Website favicon
```

## 💾 Data Storage

The application stores the shopping list in the browser's `localStorage` under the key `items`. There is **no server or database**, and the data is not synchronized between devices or browsers. Clearing the site's browser storage will remove the saved list.

## 🔮 Possible Improvements

- Edit existing items without deleting and re-adding them.
- Add categories and sorting options.
- Export or import shopping lists.
- Improve accessibility and validation feedback.
- Add optional account-based synchronization.

## 🎓 About

Created as a school web development project at **HTL Spengergasse**, demonstrating fundamental HTML, CSS, JavaScript, DOM manipulation, responsive design, and browser storage.
