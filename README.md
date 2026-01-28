# 🛒 E-Shop Nice Gadgets

Single Page Application for browsing and managing a product catalog, built with React and TypeScript.

## 📌 About the Project

This project is a product catalog SPA that implements a typical e-commerce flow: browsing products, filtering, sorting, and pagination.
The main focus is on predictable state management, clear component architecture, and proper handling of UI edge cases.


### The application includes:
- product listing,
- filtering and sorting,
- pagination,
- URL-based state synchronization,
- theme and language switching,
- swipers,
- responsive layout.

## 🌐 Live Demo

👉 [View site](https://artemyakhno.github.io/e_shop_nice_gadgets)

## 🎨 Design

👉 [Figma](https://www.figma.com/design/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog--V2--Original?m=auto&t=mooba2B721RZMFPM-6)

## 🚀 Technology Stack

### Core
- **React**
- **TypeScript**
- **React Router**

### State Management
- **React Context API** — global state for filters, theme, language, and user preferences

### Styling
- **SCSS**
- **CSS Modules**
- **Classnames**

### Libraries & Tools
- **i18next** — multilingual support
- **Swiper** — sliders
- **Debounce utility** — optimized filtering input
- **ESLint** — code quality and consistency

## ✨ Features

- Product list display with pagination
- Parameter-based filtering with debounced input handling
- Sorting (by name, price, etc.)
- State synchronization via URL search parameters
- Skeleton loading during data fetching
- UI placeholders and edge-case handling:
  - “No products found”
  - empty filter results
  - 404 page
- Theme switching (light / dark) with persistence
- Multilingual support (i18n)
- User preferences stored in localStorage
- Responsive layout
- Client-side data caching
- Global state stored and managed via React Context

## 🧠 Architectural Decisions

- Filtering and sorting logic extracted into reusable utility functions
- Debounce applied to reduce unnecessary re-renders and computations
- Theme, language, and filter state persisted in localStorage
- Skeleton components used instead of spinners for more stable UX
- Empty and error states implemented as dedicated UI components
- React Context used to avoid prop drilling and centralize shared state

## ⚙️ Installation and Setup

1. Clone the repository:
```bash
git clone https://github.com/your-username/landing_page_nothing.git
```
```bash
cd landing-page-nothing
```

2. Install dependencies:

```bash
npm install
```
or
```bash
yarn install
```


3. Run the project locally:
```bash
npm start
```
or
```bash
yarn start
```
