## TC-1: Verify no console errors on page load
**Tool:** Chrome DevTools Console  

### Steps
1. Open website
2. Open Console tab
3. Refresh page

### Expected Result
No critical JavaScript errors should appear.

### Actual Result
Pass – No console errors observed during page load.

## Observation: Missing favicon request

During Network and Console inspection, the browser automatically attempted to load `/favicon.ico`. Since no favicon file exists in the project, the request returned a 404 error.

This behavior is expected for sites without a defined favicon and does not impact functionality.


<img width="1728" height="950" alt="image" src="https://github.com/user-attachments/assets/ed4f3911-3558-4a36-9e36-d4e115b07c0d" />

