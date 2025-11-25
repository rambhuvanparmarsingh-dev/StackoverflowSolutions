# Common Use Cases for Playwright MCP Server

| Scenario                           | Example Prompt                                                                                                                          |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| **End-to-End Test Generation**         | "Generate a Playwright test to log into the application, navigate to the user profile, and update the email address."                   |
| **API Testing**                        | "Test the /api/users endpoint: Create a new user with POST, verify with GET, update with PUT, and delete with DELETE."                   |
| **UI & API Integration Test**          | "Submit the contact form via the UI, then use the API to verify the submission exists in the database."                                 |
| **Debugging a Failing Test**           | "My test login.spec.js:15 is failing. Run it, monitor the console logs, and tell me what's visible on the screen at the point of failure." |
| **Web Scraping & Data Extraction**     | "Go to the orders page, scrape the last 5 order IDs and their statuses, and list them in a table for me."                               |
| **Performance Snapshot**               | "Navigate to the homepage, take a screenshot, and measure the time it takes for the main hero image to load."                           |
| **Form Validation Testing**            | "Test the registration form: submit it empty, then with an invalid email, and verify the correct error messages appear."                |
