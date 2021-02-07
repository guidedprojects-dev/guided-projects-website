---
id: super-store-phase-2
title: Phase 2 - Display Items
sidebar_label: Phase 2 - Display Items
slug: /super-store/phase-2
---

1. **As a User, I should see a list of items on the "home" page. This should look similar to what is in the prototype.**
   -  Load data from the "/item/list" route.
   -  Create a component to display the item data. This should include [PropTypes](https://reactjs.org/docs/typechecking-with-proptypes.html) for prop type checking. It should look something like the cards on the home page of the prototype
   -  Create a container component to display a list of item components. This component should be used contain and render the Item cards
   -  Create a component that renders the rating stars and count.
      - [Full Star SVG](../../assets/star_full.svg)
      - [Half Star SVG](../../assets/star-half.svg)
      - [Empty Star SVG](../../assets/star-empty.svg)
   -  *Extra Challenge:* Make cards in the same row always be equal height
   -  *Extra Challenge:* Align "Add to Cart" Button to the bottom of the card, so all "add to cart" buttons in the row will align.
   -  *Extra Challenge:* Make the card list responsive for smaller screens. Reduce the number of cards displayed per row from three to two or one depending on the small screen size.

2. **As a User, I should see a list of only on sale items on the "deals" page**
   - This page should look and act similar to the home page, but only show items that are on sale. We don't need the search bar on this page
   - If there are no on sale items, the user should see a message stating there are no on sale items at this time.


3. **As a User, clicking on the item's title or "add to cart" button will bring me to the Item's product page**
   - Create a new React Page and route at "/item/:itemId" where *:itemId* holds the unique id of the item. This only needs to display the item's id at this point as we will add the data in the next phase
