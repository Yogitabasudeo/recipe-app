# recipe-app
Recipe Finder - Cleaned (Spoonacular)
-------------------------------------

What this is:
- A single-file React (no-build) frontend that searches Spoonacular for recipes by name or by ingredients.
- Saves favorites to localStorage.
- Designed to be clean, minimal, and ready to open in a browser.

How to use:
1. Get a Spoonacular API key at https://spoonacular.com/food-api
2. Open spoonacular_config.js and replace <YOUR_API_KEY_HERE> with your key.
3. Open index.html in a browser (or serve with a static server).

Files:
- index.html : Main app (no build required)
- spoonacular_config.js : Put your API key here
- README.md : This file

Notes:
- Spoonacular API keys have rate limits on free plans.
- For production, proxy the API key on a server to avoid exposing it on the client.
