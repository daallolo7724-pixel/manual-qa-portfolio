# Shopping Cart – Test Execution Results

**Application:** Shopping Application  
**Test Environment:** Test Environment  
**Execution Type:** Manual Testing

## TC-005 – Add product to shopping cart

- **Test Case:** Add product to shopping cart
- **Test Data:** Laptop – $999
- **Expected Result:** Product is added successfully, quantity is 1, and total is $999.
- **Actual Result:** Product was added successfully, quantity displayed 1, and total displayed $999.
- **Status:** PASS
- **Linked Bug:** N/A

## TC-006 – Update product quantity

- **Test Case:** Update product quantity
- **Test Data:** Laptop – $999, quantity changed from 1 to 2.
- **Expected Result:** Quantity updates to 2 and total recalculates to $1,998.
- **Actual Result:** Quantity updated to 2, but total remained $999.
- **Status:** FAIL
- **Linked Bug:** KAN-6
- **Severity:** Critical
- **Priority:** High

**Execution Summary:**
- Total Test Cases Executed: 2
- Passed: 1
- Failed: 1
- Pass Rate: 50%

**Note:** These are simulated test execution results for learning and portfolio purposes.
