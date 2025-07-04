# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

React GitHub Info Website

This is a simple multi-page React website built using React Router and Tailwind CSS. 
It includes a navigation header, footer, and multiple routes such as Home, About, Contact, GitHub, and dynamic User pages.

---

#🚀 Features

- 🌐 Navigation Bar with links: Home, About, Contact, GitHub, User
- 👤 GitHub Tab: Displays followers and avatar using GitHub public API
- 🔍 Dynamic User Page: Enter any user ID in the URL (e.g. `/user/adityajoshi-sorce`) to view the username
- 🎨 Styled with Tailwind CSS
- ⚛️ Powered by React Router v6.4+

---

🧠 How It Works

- The GitHub page uses a `loader` function to fetch GitHub user data.
- The User page uses `useParams()` from `react-router-dom` to extract the username from the URL and display it.



