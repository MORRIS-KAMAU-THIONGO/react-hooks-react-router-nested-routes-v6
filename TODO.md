# TODO List for Implementing Nested Routes

- [x] Update `src/routes.js`: Set App as parent route with errorElement, and children: Home (with nested UserProfile), About, Login.
- [x] Update `src/App.js`: Add NavBar in header, import Outlet, fetch users in useState/useEffect, pass users to Outlet context.
- [x] Update `src/pages/Home.js`: Remove NavBar, use useOutletContext to get users, render userList, add Outlet for nested routes.
- [x] Update `src/pages/UserProfile.js`: Use useOutletContext to get users, find user by params.id instead of fetching.
- [ ] Run `npm start` to test the app.
- [ ] Navigate to / to see Home with users, click profile link to see nested UserProfile.
- [ ] Ensure NavBar appears on all pages.
