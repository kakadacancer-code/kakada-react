# My Cosmetic Project using React

## Feature

- Add, Edit, and Delete tasks
- Responsive Design

## Tech Stack

- React.js 
- Javascript
- CSS
- HTML
- React Router
- Context API
- localStorage
- lucide-react

# 1. Install packages
npm install

# 2. Start development server
npm run dev

# 3. Build for production (optional)
npm run build


### Structure Project

kakada-react/
│
├── public/
│   └── images/
│
├── src/
│   │
│   ├── assets/
│   │   ├── images/
│   │   └── icons/
│   │
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   ├── Navbar.jsx
│   │   └── Button.jsx
│   │
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── About.jsx
│   │   ├── Products.jsx
│   │   ├── Contact.jsx
│   │   └── Login.jsx
│   │
│   ├── layouts/
│   │   └── MainLayout.jsx
│   │
│   ├── context/
│   │   ├── AuthContext.jsx
│   │   └── CartContext.jsx
│   │
│   ├── hooks/
│   │   └── useFetch.js
│   │
│   ├── services/
│   │   └── productService.js
│   │
│   ├── utils/
│   │   └── formatPrice.js
│   │
│   ├── styles/
│   │   └── global.css
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
