# Torrent-to-Drive-Selective  

**Disclaimer:** This method is against Google Colab's policies. Use it at your own discretion.  

## Overview  
This repository provides Jupyter notebooks to transfer files from torrents or direct download links to Google Drive.  

### 1. Torrent to Drive (`torrent_to_drive.ipynb`)  
This notebook allows you to download torrent files directly to your Google Drive.  

#### Usage:  
1. Download the `torrent_to_drive.ipynb` file and upload it to Google Colab.  
2. Run all cells sequentially.  
3. Your files will be saved to your Google Drive.  

**Note:** It is recommended not to use your personal Google Drive account for this.  

### 2. Direct Link to Drive (`direct_link.ipynb`)  
This notebook enables transferring files from direct download links to Google Drive.  

#### Usage:  
1. Download and upload `direct_link.ipynb` to Google Colab.  
2. Run all cells sequentially.  
3. Alternatively, use the following command to save a file directly to Google Drive:  
   ```bash
   !wget -P /content/drive/My\ Drive/ "paste your direct link here"

### How to Get Direct Download Links  
- **Desktop:** Add the file to your downloads in Firefox/Chrome, then right-click on it and select **Copy Link**.  
- **Android:** Use the [1DM](https://play.google.com/store/apps/details?id=idm.internet.download.manager) app. Before adding the file for download, an option to **Copy Link** will be available.  
