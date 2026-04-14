# QUICK START: Deploying Google Sheets and Google Apps Script

## Introduction
This guide provides step-by-step instructions on how to deploy a Google Sheets application using Google Apps Script.

## Prerequisites
- A Google account
- Basic knowledge of JavaScript

## Step 1: Creating a New Google Sheet
1. Go to [Google Sheets](https://sheets.google.com).
2. Click on the `Blank` option to create a new spreadsheet.

## Step 2: Opening the Apps Script Editor
1. In your new spreadsheet, click on `Extensions`.
2. Select `Apps Script`.

## Step 3: Writing Your Apps Script
1. In the Apps Script editor, replace any existing code with the following example code:

   ```javascript
   function myFunction() {
       Logger.log("Hello, World!");
   }
   ```

2. Click on the disk icon to save your project. Name it appropriately.

## Step 4: Running Your Script
1. Click the play icon (▶) to run your script.
2. Check the logs by clicking on `View` -> `Logs`.

## Step 5: Triggering a Function Automatically (Optional)
1. In the Apps Script editor, click on `Triggers` (the alarm clock icon).
2. Click on `Add Trigger`.
3. Set your desired function, event source, and event type.
4. Click `Save`.

## Step 6: Sharing Your Google Sheet
1. Click on the `Share` button in the top right corner of the Google Sheets interface.
2. Enter the email addresses of users you wish to share with and set the permissions.

## Conclusion
You have successfully deployed a Google Sheets application with Google Apps Script. You can now customize your script further as per your requirements.

For more detailed information, visit the official [Google Apps Script documentation](https://developers.google.com/apps-script).