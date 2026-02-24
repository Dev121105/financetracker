# FinTracker (Finance Tracker)

A modern, responsive personal finance management application built with **React**, **Firebase**, and **Ant Design**. FinTracker helps you keep track of your income and expenses, visualize your spending habits through interactive charts, and manage your financial data effortlessly.

---

## 🚀 Features

- **Transaction Management:** Easily add, edit, and delete income and expense transactions.
- **Visual Analytics:** View your financial data through beautifully rendered Line and Pie charts using Ant Design Charts.
- **Data Table:** Comprehensive and sortable table view of all your transactions.
- **CSV Data Import/Export:** Seamlessly import or export your transaction data using CSV files (powered by PapaParse).
- **Secure Authentication:** User authentication and secure cloud database utilizing Firebase Auth and Firestore.
- **Responsive Design:** Crafted with Tailwind CSS to ensure a great user experience on both desktop and mobile devices.
- **Real-time Notifications:** Toast notifications for instant feedback on your actions.

## 🛠️ Tech Stack

- **Frontend Framework:** [React 18](https://reactjs.org/)
- **Routing:** [React Router v6](https://reactrouter.com/)
- **UI Components:** [Ant Design](https://ant.design/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Backend & Database:** [Firebase](https://firebase.google.com/) (Authentication & Firestore)
- **Charts:** [@ant-design/charts](https://charts.ant.design/)
- **State Management:** [React Firebase Hooks](https://github.com/CSFrequency/react-firebase-hooks)
- **Alerts/Toasts:** [React Toastify](https://fkhadra.github.io/react-toastify/)

## 📂 Project Structure

```text
financetracker/
├── public/               # Public assets (index.html, logos, etc.)
├── src/                  # Source code
│   ├── components/       # Reusable React components (Dashboard, Header, Cards, Modals, etc.)
│   ├── firebase.js       # Firebase configuration and initialization
│   ├── App.js            # Main Application component & Routing
│   ├── index.js          # App entry point
│   └── index.css         # Global Tailwind CSS imports
├── package.json          # Project dependencies and scripts
└── README.md             # Project documentation
```

## 💻 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- A Firebase project

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Dev121105/Fin-Tracker.git
   cd Fin-Tracker
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure Firebase:**
   - Create a new project on the [Firebase Console](https://console.firebase.google.com/).
   - Enable **Authentication** (e.g., Email/Password or Google Sign-In).
   - Enable **Firestore Database**.
   - Create a `.env` file in the root of the project and add your Firebase configuration:
     ```env
     REACT_APP_FIREBASE_API_KEY=your_api_key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
     REACT_APP_FIREBASE_PROJECT_ID=your_project_id
     REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
     REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
     REACT_APP_FIREBASE_APP_ID=your_app_id
     ```

4. **Run the development server:**
   ```bash
   npm start
   ```
   The app will automatically open at [http://localhost:3000](http://localhost:3000).

## 🌍 Deployment

This project is configured and ready to be deployed on platforms like **Vercel** or **Netlify**.

To create an optimized production build, run:
```bash
npm run build
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 📝 License

This project is licensed under the MIT License.
