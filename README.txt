TRAVELSPLIT — iPhone web-app setup (public-safe code)

The downloadable HTML link in ChatGPT may not run as a website on iPhone.
Publish this code as a web app using GitHub Pages, then import your PRIVATE JSON file.

SETUP (using browser on phone or computer):
1. Unzip TravelSplit_Website_Kit.zip to extract index.html.
2. In github.com, create a PUBLIC repository, e.g. travelsplit-app.
3. Upload ONLY index.html to the root of that repository. Do not upload the JSON backup.
4. Repository > Settings > Pages > Build and deployment > Deploy from a branch > main / root > Save.
5. When Pages shows the website URL, open it in Safari. The URL generally looks like https://USERNAME.github.io/travelsplit-app/.
6. In the app, press Restore backup, select TravelSplit_Private_China_Expenses.json.
7. In Safari > Share > Add to Home Screen (optional).

PRIVACY: Public GitHub Pages makes the app SOURCE CODE public, but this kit does NOT contain the user's private transactions. The separate JSON backup contains the historical financial entries. Do NOT upload that JSON to GitHub.

This app stores new entries in Safari's local browser storage on each device, without cloud sync. Use Backup JSON frequently. Offline usage requires the page to stay cached; hosting alone does not guarantee offline behavior. CNY/BDT rate is manually editable, not live. ChatGPT smart parsing is an optional copy/paste flow, not a connected API.
