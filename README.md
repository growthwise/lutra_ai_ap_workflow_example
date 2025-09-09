# What You need

1. A Lutra AI Account. You can sign up to Lutra here (https://lutra.ai)
2. A Google Drive account
3. A Xero account (demo is fine) if you want to sign up to a Xero demo account go here https://www.xero.com/au/signup/

### Setting Everything Up in Google Drive

Once you've setup all acocunts you need to do the following in Google Drive

1. Create a folder, you can name it whatever you like but in the video we called it LutraExample
2. Extract the folder "ID" from the URL you can do this by clicking into the address bar whilst inside the folder and copying the end of the URL https://drive.google.com/drive/u/0/folders/*[thisparthere]*
3. Keep note of that folder ID
4. Within the same folder, create another folder, in the video we called it processed and follow the same steps above to copy and save the ID somewhere
5. Upload some bills to pay to the first folder, you can use the same ones in the video by downloading them from here https://github.com/growthwise/lutra_ai_ap_workflow_example/tree/main/invoices

### Connecting Lutra AI to Tools ###

Login to Lutra, click on Tools and conect to "Drive", "Sheets" and "Xero" you can be selective with the scopes but in the video we had all scopes enabled for simplicity. You should
have already setup all of these accounts earlier. 

### The Prompt ###

You are a bookkeeping assistant and need to create bills in Xero. 
There are PDF files stored in this Google Drive folder with ID [Use your invoice folder ID Here] 
For each file in this folder read the PDF file and extract its data. Connect to Xero and find an appropriate expense code using your own best judgement based on the extracted data, avoid using general expenses and create the bill entries
                                                                                                                                                     
Upon successful creation of the bills move the processed PDF’s from the root folder to the processed folder in Google drive with ID [Use your processed folder ID here]                
Create a Google Sheet in the root folder that lists the processed documents as well as the invoice ID that was created in Xero.


Once you've entered the prompt above press the play button. Remember to be accurate with your folder ID's!

### Youtube Video Link ###

### Lutra Playbook Share Link ###

If you just want to directly try the playbook the link is here https://lutra.ai/shared/KVI_Jaolofg             
