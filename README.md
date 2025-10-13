# Overview
This is a minimal static web page that clearly displays the message: "Render is live". It includes a subtle, accessible status indicator and modern styling.

# Setup
No build tools or dependencies are required.

- Option 1: Open index.html directly in any modern web browser.
- Option 2: Serve it as a static site using any HTTP server (e.g., Python http.server, Node http-server, Nginx, etc.).

# Usage
- Open index.html to see the status message.
- To host locally:
  - Python 3: python -m http.server 8080 (then visit http://localhost:8080)
  - Node (http-server): npx http-server -p 8080 (then visit http://localhost:8080)
- To customize the message or colors, edit the text content or CSS variables in the <style> block.