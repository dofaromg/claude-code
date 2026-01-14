---
allowed-tools: playwright-browser_navigate, playwright-browser_wait_for, playwright-browser_take_screenshot, playwright-browser_snapshot, playwright-browser_close
description: Capture a screenshot of a webpage
---

## Your task

Capture a screenshot of the specified webpage URL.

## Steps

1. Navigate to the URL provided by the user
2. Wait for the page to load completely using `playwright-browser_wait_for` (wait at least 2-3 seconds after navigation)
3. Take a screenshot of the page using `playwright-browser_take_screenshot`
4. Save the screenshot with an appropriate filename (e.g., including domain and timestamp)
5. Close the browser when done using `playwright-browser_close`

## Important notes

- Always wait for the page to fully load before taking a screenshot to ensure all content is rendered
- Use a descriptive filename for the screenshot that includes the domain name and timestamp
- Handle any errors gracefully and inform the user of any issues
- Always close the browser after capturing the screenshot to free up resources
- If the page fails to load, provide a clear error message to the user
