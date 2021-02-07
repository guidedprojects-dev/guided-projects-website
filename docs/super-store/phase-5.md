---
id: super-store-phase-5
title: Phase 5 - Adding Items to Cart
sidebar_label: Phase 5 - Adding Items to Cart
slug: /super-store/phase-5
---

1. **Create a "cart state" for the application**
   - You can implement this however you like. Use something like Redux, or React Context API. I would recommend Context API because it isn't going to be a very big state and a library might be overkill.
   - We need to have the ability to add, remove, and update individual items.

2. **As a User, Clicking "Add Item" will add my item to my cart with the specified quantity**
   - Adding the item will add the item to the cart state.
   - Adding items to the cart after an item has initially been added should just update the "in cart" count.
   - The user should see a notification / alert on the screen letting them know they added the item successfully.
   - Added items will show up in a list view at the /cart route


3. **As a User, I can see how many of an item I have in my cart when I view that item's page**
   - If the user goes back to an item that is in their cart, they should see a message that informs them of how many of that item are currently in their cart


4. **As a User, I should see a notification in my cart if my cart is empty**
   - Just show the user something about their cart being empty when they view the cart page with nothing in their cart. Otherwise it looks weird having an empty page.


5. **As a User, I can update the "in cart count" of items in my cart at the /cart route**
   - Users should be able to adjust the number of items they have in their cart on the cart page. They should not be able to change the count to more than the stock count, or below 0.


6. **As a User, I can remove Items from my cart**
   - Users should be able to remove items from their cart by either clicking a "remove" button, or updating their "in cart count" to 0


7. **As a User, I can see the total of all my items at the bottom of the cart page**


8. **As a User, I can see a pill notification on the cart nav button that shows the number of items in my cart**
   - Add a pill that displays the total count of items in the user's cart