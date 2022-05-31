# ObjectDetectionLabeling
[Internal Use Python 3.10] Auto-clicker for Object Detection dataset labeling.

To avoid making people hassel with API authorization and authentication, I had to make this program a little scuffed.
To use this, you will need to DOWNLOAD the contents of the GoogleSheet into a Microsoft Spreadsheet. 
Then you will need to input the path of your downloaded file into the program for it to run.
It may require you to open up a window in Microsoft Edge if it doesn't initially work.
Once you are done, you will have to upload the contents of the Microsopft Spreadsheet back to the Google Drive.
You may also want to convert the file back to a GooleSheet once uploaded by clicking File -> Save as Google Sheets

This program is listening for keyboard inputs the entire time it is running, so you must exit whenever you are not labeling data. 
It is easiest if you open a new window before starting.
Once it is running, you should not need to click anything. Simply pressing the arrow keys will input your answer into the dataset, change to the next picture, and save your spreadsheet for you when you exit. 

# NOTE
If the program starts to compain about the file it is likely because the file is corrupted and a new copy should be used