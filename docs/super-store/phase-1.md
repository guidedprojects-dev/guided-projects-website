---
id: super-store-phase-1
title: Phase 1 - Setup
sidebar_label: Phase 1 - Setup
slug: /super-store/phase-1
---

1. **As a Developer, I should be able to run the app with `yarn start` or `npm start`**
    - We just want to get the base app working. There doesn't have to be anything special about it.


2. **As a Developer, I should have access to a css style sheet in my application**
    - For this task, you can load in any stylesheet you'd like, or make your own if you are into that. We don't want to opt for something like [Material UI](https://material-ui.com/) in this case, because we want practice creating our own components from a stylesheet.


3. **As a User, I should see links for "Home", "Deals", and "Cart" in the navbar, along with a Company Logo**


4. **As a User, navigating to "/", "/deals" and "/cart" via the menu should switch the contents of the page. Navigating should not reload the page.**
    - Use a router such as [React Router](https://reactrouter.com/) to implement page navigation. Each link "/", "/deals", and "/cart" should render a new page in the body of the application. The page doesn't have to have anything fancy on it at this point, it can just be text, but it should be different on each page.


5. **As a User, the nav item for the page I am on should appear "active"**
    - When a user clicks on a navlink to navigate to a different page, that navlink should appear "active" by applying some styling to it that distinguishes it from the other navlinks
