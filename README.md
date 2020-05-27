# canvas_api_scripts
collection of Google Apps Scripts in JavaScript for working with Canvas API

This code is developed as a tool to automate team formation in the Canvas LMS.  The GUI for this code is intended to be a google sheet, but I'm not sure how to load a google sheet to Git.  The spreadsheet should have three sheets; 'Admin', 'Canvas_Download', and 'CATME Import'.  The Canvas course ID should be in the Admin sheet, along with a token to access the Canvas site.  I'm working to get OAuth2 incorporated, but I have no idea how to do that.

The code is wrtten in JavaScript and uses the Google Apps Scripts environment (e.g. verbose logging in a google doc).
