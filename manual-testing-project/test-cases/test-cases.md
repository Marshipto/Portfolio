# Manual Test Cases

## Module: Authentication / Account

### TC-001 – Required Fields Validation on Login
**Steps:**
1. Open the Login page
2. Leave username and password fields empty
3. Click “Sign in”
**Expected Result:**
Error message displayed indicating both fields are required.
**Priority:** High

### TC-002 – Login With Invalid Credentials
**Steps:**
1. Enter a valid username
2. Enter an incorrect password
3. Click “Sign in”
**Expected Result:**
System shows “invalid credentials” and does not allow access.
**Priority:** High

### TC-003 – Email Format Validation
**Steps:**
1. Enter an invalid email format (e.g., “user@@test”)
2. Attempt to submit login
**Expected Result:**
System displays “invalid email format” or prevents submitting.
**Priority:** Medium

## Module: General Navigation

### TC-004 – Main Menu Navigation
**Steps:**
1. Open the home page
2. Click each option in the top navigation menu
**Expected Result:**
Each option opens the correct section/page.
**Priority:** Medium

### TC-005 – Validate External Links
**Steps:**
1. Scroll to the footer
2. Click all external links (policies, support, social media)
**Expected Result:**
Links open correctly and display expected content.
**Priority:** Low

### TC-006 – Responsive Layout Validation
**Steps:**
1. Resize browser window to mobile resolution
2. Inspect header, menu, and main content
**Expected Result:**
Layout adapts correctly without breaking elements.
**Priority:** Medium

## Module: Search

### TC-007 – Search With Valid Keyword
**Steps:**
1. Enter a valid term in the search bar
2. Press Enter
**Expected Result:**
Relevant search results are displayed.
**Priority:** High

### TC-008 – Search With Non-Existing Keyword
**Steps:**
1. Enter a random or nonsense keyword
2. Press Enter
**Expected Result:**
System displays a “no results found” message.
**Priority:** Medium

### TC-009 – Empty Search Submission
**Steps:**
1. Leave the search bar empty
2. Submit the search
**Expected Result:**
System prevents the search or displays an informative message.
**Priority:** Low

## Module: Cart / Forms / Core Flow

### TC-010 – Add Item to Cart
**Steps:**
1. Navigate to any product
2. Click “Add to cart”
**Expected Result:**
Cart updates (counter increases) and product is listed in cart.
**Priority:** High

### TC-011 – Form Validation With Missing Required Fields
**Steps:**
1. Open any form that includes required fields
2. Attempt to submit without entering mandatory data
**Expected Result:**
Validation messages appear for each missing required field.
**Priority:** High

### TC-012 – Complete Core User Flow
**Steps:**
1. Log in
2. Navigate to a product or target page
3. Add item to cart or fill out form
4. Confirm or finish the flow
**Expected Result:**
Flow completes end-to-end without errors.
**Priority:** High
