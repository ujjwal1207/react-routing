# React Router Demo

A simple React project demonstrating routing, dynamic routes, and reusable layout components using React Router.

## Tech Stack

- **React** – For building the user interface and managing state.
- **Vite** – For fast development and build tooling.
- **Tailwind CSS** – For utility-first, responsive styling.
- **React Router** – For client-side routing and navigation.

## Features

- **Header and Footer**: Reusable layout components rendered on every page.
- **Nested Routing**: Uses `<Outlet />` to render child routes within the main layout.
- **Dynamic Routes**: Supports dynamic user pages (e.g., `/user/123`) using React Router's `useParams` hook.
- **Responsive Design**: Styled with Tailwind CSS for a modern look.

## How It Works

- The `App.jsx` file sets up the main layout with a header, footer, and an `<Outlet />` for nested routes.
- The `User.jsx` component uses `useParams` from React Router to read the dynamic `userid` from the URL and display it.
- The `Footer` and `Header` components are always visible, regardless of the current route.

## Example Dynamic Route

Visiting `/user/42` will render:

```
User: 42
```

## React Router Concepts Used

- **Outlet**: For nested routing and layouts.
- **useParams**: To access dynamic route parameters.
- **Link**: For navigation between routes (used in header/footer).
- **Route**: For defining static and dynamic routes.

## Usage

1. **Clone the repository:**
   ```sh
   git clone https://github.com/ujjwal1207/reactrouting.git
   cd routerpage
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Start the development server:**
   ```sh
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## License

This project is licensed under the MIT License.
