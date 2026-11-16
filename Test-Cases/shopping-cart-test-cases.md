
# Shopping Cart – Test Cases

## TC-005: Add product to shopping cart

**Test Type:** Functional / Positive

**Preconditions:**
- User is logged in.
- Product is available.

**Test Steps:**
1. Open the product catalog.
2. Select an available product.
3. Click "Add to Cart".
4. Open the shopping cart.

**Test Data:**
- Product: Laptop
- Quantity: 1

**Expected Result:**
The selected product should appear in the shopping cart with the correct price and quantity.

**Status:** Not Executed

---

## TC-006: Update product quantity

**Test Type:** Functional / Positive

**Preconditions:**
- User is logged in.
- Shopping cart contains one product.

**Test Steps:**
1. Open the shopping cart.
2. Change the product quantity from 1 to 2.
3. Check the displayed quantity.
4. Check the total price.

**Test Data:**
- Initial quantity: 1
- New quantity: 2

**Expected Result:**
The product quantity should update to 2 and the total price should be recalculated correctly.

**Status:** Not Executed

---

## TC-007: Remove product from shopping cart

**Test Type:** Functional / Positive

**Preconditions:**
- Shopping cart contains at least one product.

**Test Steps:**
1. Open the shopping cart.
2. Click "Remove" on the selected product.
3. Review the shopping cart.

**Expected Result:**
The selected product should be removed from the shopping cart and the total should update accordingly.

**Status:** Not Executed

---

## TC-008: Add unavailable product to shopping cart

**Test Type:** Negative

**Preconditions:**
- A product is marked as unavailable or out of stock.

**Test Steps:**
1. Open the product catalog.
2. Select an unavailable product.
3. Attempt to add it to the shopping cart.

**Expected Result:**
The application should prevent the product from being added and display an appropriate message.

**Status:** Not Executed

---

## TC-009: Add multiple units of a product

**Test Type:** Functional / Positive

**Preconditions:**
- User is logged in.
- Product has sufficient stock.

**Test Steps:**
1. Open the product catalog.
2. Select an available product.
3. Set the quantity to 3.
4. Click "Add to Cart".
5. Open the shopping cart.

**Test Data:**
- Product: Laptop
- Quantity: 3

**Expected Result:**
The shopping cart should display the selected product with a quantity of 3 and the correct calculated total.

**Status:** Not Executed
