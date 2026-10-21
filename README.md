# Jolly Search Engine

Includes:
- `index.html`: Search form pointing to `results.html` in a new tab.
- `results.html`: Displays query & calls `/.netlify/functions/ask` for "Jolly's Answer".
- `netlify/functions/ask.js`: Netlify serverless function connecting to Gemini API.
- `netlify.toml`: Deployment config for Netlify.
