# How this app work?

You search for an item, you select a region/country, the app searches for the item in every shops that can find, and then gives you a table with the Product Name, Estimated Price, Country, Domain and Website. The table can be saved as a CSV, and the app has a history function to show you past searches.

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

## Disclaimer

This application is a demo who still contains error when it comes to webscrapping of value of items and links to the online shops webpages. 
