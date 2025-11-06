# 🐾 Adopt-a-Pet | React Router v6 Practice Project
```text
This project is a hands-on build designed to learn and implement React Router v6 using real-world routing patterns, nested routes, URL parameters, redirects, and query strings.

It displays adoptable pets by type, allows users to view detailed information, handles search queries, and gracefully routes to a custom “Pet Details Not Found” page when a resource is missing.
```
---

## ✅ Key Features

## ✅ React Router v6 with:
```text
createBrowserRouter + createRoutesFromElements

Nested routes and layout rendering using <Outlet />

Dynamic URL params (/:type, /:type/:id)

URL search queries with useSearchParams

Programmatic navigation using useNavigate

Fallback redirect on missing pet data (Navigate → /pet-details-not-found)
```
---

## ✅ Reusable components
```text
Navigation bar that highlights the active route using <NavLink>

Search bar with controlled routing to /search?name=

Hero component and card-style pet previews
```
---

## ✅ Data fetching
```text
API helper functions (mocked Petfinder logic)

Loading and error states

Conditional rendering depending on results
```
---

## ✅ Custom 404-style experience
```text
When a pet ID is invalid or missing, user is routed to a fun PetDetailsNotFound page with an image and a “Go Home” button
```
---

## ✅ Technologies Used

- React 18

- React Router v6

- JavaScript (ES6+)

- JSX & functional components

- useState, useEffect, useNavigate, useParams, useSearchParams

- CSS and layout styling included from Codecademy starter files

✅ What I Learned

- How createBrowserRouter replaces older <BrowserRouter> syntax

- The difference between Link and NavLink

- How URL parameters and query strings map to component props

- Gracefully handling API failures with redirects

- Cleaner routing file structure using pages + components folders

- Better commit discipline with feature-based commits

✅ Running the project locally
# install dependencies
- npm install

# run dev server
- npm start

# view at:
- http://localhost:3000

## Learn More

- You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

- To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

- This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

- This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

- This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

- This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

- This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

- This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)