# Search Feature Test Cases

## Test Case 1 — Search for existing product

**Test ID:** TC_SEARCH_001  
**Scenario:** User searches for an existing product

Steps:
1. Navigate to homepage
2. Enter product name in search bar
3. Click search

Expected Result:
Product related to the search term should be displayed.


---

## Test Case 2 — Search for non-existing product

**Test ID:** TC_SEARCH_002  
**Scenario:** User searches for a product that does not exist

Steps:
1. Navigate to homepage
2. Enter random text
3. Click search

Expected Result:
System should display message "No results found".


---

## Test Case 3 — Empty search

**Test ID:** TC_SEARCH_003  
**Scenario:** User clicks search without entering text

Steps:
1. Navigate to homepage
2. Leave search field empty
3. Click search

Expected Result:
System should display validation message.
