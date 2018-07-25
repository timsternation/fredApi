# fredApi
Written in Google Apps Script, this code is designed to query the Fred API to pull data for series specified by the user.

To use:
1. Register an API key here: https://research.stlouisfed.org/useraccount/apikeys
  1a. You will need to create an account at the site first if you don't have one already. This is free to do.
  
2. Create the Google Sheet where you'll be stashing the data. For each data series you want to capture, create a tab and label it with the code of the series you want (e.g. CIVPART for the labor force participation rate)

3. Paste code from script into a new Apps Script file in your Google Drive. Follow instructions contained in the script to see where to past your sheet ID and your API key.

4. In the Apps Script editor, run "My Function" up at the top.

5. Sit back and relax as that sweet, sweet data comes pouring in.
