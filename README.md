# ObjectDetectionLabeling
[Internal Use][Python 3.10] Auto-clicker for Object Detection dataset labeling.

To avoid making people hassel with Google API authorization and authentication, I had to make this program a little scuffed.
Download the contents of the GoogleSheet as a .xlsx Spreadsheet. Then input the path of your downloaded file into the program.
Open a browser window if one is not currently open.
Once all the data is labeled, save the file as a Google Sheet and upload the contents of the spreadsheet back to the Google Drive.

This program is listening for keyboard inputs the entire time it is running, so you must exit whenever you are not labeling data. 
Once it is running, you should not need to click anything. Simply pressing the arrow keys will input your answer into the dataset, change to the next picture, and save your spreadsheet for you when you exit. 
