# fredApi
Written in Google Apps Script, this code is designed to query the Fred API to pull data for series specified by the user.

## First version - FredQuery_v1:

To use:
1. Register an API key here: https://research.stlouisfed.org/useraccount/apikeys
  1a. You will need to create an account at the site first if you don't have one already. This is free to do.
  
2. Create the Google Sheet where you'll be stashing the data. For each data series you want to capture, create a tab and label it with the code of the series you want (e.g. CIVPART for the labor force participation rate)

3. Paste code from script into a new Apps Script file in your Google Drive. Follow instructions contained in the script to see where to past your sheet ID and your API key.

4. In the Apps Script editor, run "My Function" up at the top.

5. Sit back and relax as that sweet, sweet data comes pouring in./*

## Second version - FredQuery_v2:

This is an updated version of the script, which is developed for the specific purpose of providing 
data for a dashboard I'm building in Excel.

The output gets written to whatever Google sheet the script is associated with. I have also included 
a sheet in my Google Sheets file with some metadata on the different series.

Limitations of the below script are that it is not as customizable, so to add more series and 
units will require edits to the script itself. Adding more units in particular requires edits throughout.

Here is the FredAPI documentation: https://fred.stlouisfed.org/docs/api/fred/

Here is a link to a template Google Sheet: https://docs.google.com/spreadsheets/d/1AASRX4rTAaOTWJMBe7HOhU2qgTICq8OFSx7prnip3lQ/edit?usp=sharing

To access the script within the dummy Google sheet, click 'tools' and then 'script editor'

Don't forget to put your own API key in at line 88!
