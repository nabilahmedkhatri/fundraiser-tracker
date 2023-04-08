## Usage instructions
1. Create a Google cloud project: https://developers.google.com/workspace/guides/create-project
2. Enable Workspace APIs for project: https://developers.google.com/workspace/guides/enable-apis
3. Look for Google Sheets API and then enable the Google Sheets API
4. Create credentials to use the API
5. Click "User data"
6. Give app details
7. Add "http://localhost:8000" to Authorized Javascript origins
8. Copy the client id
9. Clone this repository, update client id from step 8 into this file where it says YOUR_CLIENT_ID
10. In the credentials section for your google project, click Create Credentials > API Key. Copy this API key and updated index.html where it says YOUR_API_KEY
11. Make a copy of this template file: https://docs.google.com/spreadsheets/d/13wNI5F8heM1d6pN_VJagGEo_54_-NewnIVvkkkyyWew/edit?usp=sharing
12. In the URL of your file get the id of the spreadsheet: https://docs.google.com/spreadsheets/d/13wNI5F8heM1d6pN_VJagGEo_54_-NewnIVvkkkyyWew/edit#gid=0 in this example the id is `13wNI5F8heM1d6pN_VJagGEo_54_-NewnIVvkkkyyWew` 
13. Update this ID in index.html where it says YOUR_SPREADSHEET_ID 
14. Once updated run `python3 -m http.server 8000` to start the application
15. Open the webpage adn click Authorize
16. Once authorized the tracker will update data from spreadsheet
