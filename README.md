# Grocery Shopping List

This project demonstrates a simple implementation of a grocery shopping list using JavaScript. It showcases array operations such as adding, removing, and updating items, along with generating dynamic messages to display the current list.

## Features

- **Dynamic List Management**: Items can be added to or removed from the list dynamically.
- **Real-Time Updates**: The shopping list reflects the latest changes immediately.
- **Array Operations**: Demonstrates usage of array methods such as `push`, `pop`, `unshift`, and `shift`.

## Code Overview

### Main Functionality

1. **Initial State**:
   - Starts with an empty shopping list (`shoppingList`).

2. **Adding Items**:
   - Adds items like "Apples" and "Grapes" using the `push()` method.
   - Prepends items like "Vegetable Oil" using the `unshift()` method.

3. **Removing Items**:
   - Removes the last item using the `pop()` method.
   - Removes the first item using the `shift()` method.

4. **Updating Items**:
   - Directly updates specific items in the list, such as replacing "Vegetable Oil" with "Canola Oil".

5. **Message Display**:
   - Uses the `getShoppingListMsg` function to format and return the current shopping list as a string.
