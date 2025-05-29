# nature-near-me-poc
Nature Near Me - POC (The "Vibe Code" Edition)
So, I just 'vibe coded' this up for someone who wanted a quick mock-up of their "Nature Near Me" app idea. Yeah, I know, pure HTML/CSS/JS in a single file – I've betrayed the front-end community, send help (or snacks). Anyway, it's a proof of concept, not a production masterpiece!
Project Overview
This is a simple, client-side Proof of Concept (POC) for an application called "Nature Near Me." The goal is to demonstrate how a user could find nearby nature spots within a specific region (Gauteng, South Africa, in this demo) using embedded data. It simulates an offline-capable experience once the page is initially loaded.
Key Features
 * Offline-like Experience: Uses embedded data, so once loaded, searching and browsing spots doesn't require an active internet connection.
 * Location-Based Search: Allows users to (conceptually) use their current location (via browser Geolocation API) to find nearby spots.
 * Keyword Search: Users can manually type in keywords, city names, or types of nature spots to filter the list.
 * Embedded Dataset: Contains a curated list of ~15 nature spots in Gauteng for demonstration.
 * Simple UI: Built with HTML, Tailwind CSS (via CDN), and Vanilla JavaScript.
 * Direct Links to Maps: Provides links to Google Maps for directions to the selected nature spot.
Technology Stack
 * HTML
 * Tailwind CSS (via CDN)
 * Vanilla JavaScript
How to Run Locally (If you really want to)
 * Save the index.html file (the one containing everything).
 * Open it directly in your web browser.
   * Note: For Geolocation API to work reliably, you might need to serve it via a local HTTP server (e.g., VS Code Live Server, Python's http.server, or npx http-server).
Deployment
This project is deployed using GitHub Pages.
Disclaimer: This is a rapidly developed mock-up for illustrative purposes only.
