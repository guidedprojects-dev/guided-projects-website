---
id: super-store-phase-4
title: Phase 4 - Search and Pagination
sidebar_label: Phase 4 - Search and Pagination
slug: /super-store/phase-4
---

1. **As a User, I can search items on the home page using the search bar**
   -  Create a component the implements the search bar design with a text input and a "search" button
   -  Consuming components should be able to pass in an "onSearch" prop that is a function.
   -  Clicking the "search" button, or pressing enter while typing into the search bar will run the "onSearch" handler with the text from the search input in the first parameter position.
   -  If the search yeilds no results, the user should see a message that informs them there are no results for the search query.


2. **As a User, clearing the search bar will reset my search**
   -  Requery all items when the user resets the search.
   -  Pressing escape while focused on the search input should clear the input.
   -  Pressing the "x" button next to teh search input should clear the input.


3. **As a User, If there are no results for my search, I should see a message letting me know there are no results.**
   - Just show some dialog letting the user know there are no results so the page is not empty.


4. **As a User, I can page through items**
   -  The user can change pages to the first, last, next and previous page by clicking the corresponding buttons
   -  If the user is on the first page, the "previous" and "first" buttons should be disabled
   -  If the user is on the last page, the "next" and "last" buttons should be disabled
   -  Changing pages should rerun the query to load the items for the appropriate page
   -  Changing the pages should scroll the user to the top of the page.