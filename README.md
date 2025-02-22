# torrent-to-drive-selective
This is against Google Colab policy and you shouldn't be using it.

You can use this torrent_to_drive.ipynb to convert torrent files to drive.

1.download the ipynb file and upload in google colab and run all the cells accordingly
2.Then BOOM files are in your drive
3.I recommend not to use personal Drive account

You can use direct_link.ipynb to convert direct download links to drive

 Same instructions as above and 
  !wget -P /content/drive/My\ Drive/ "paste your direct link here"

To get the direct link for any files
for desktop just add to download in your firefox/chrome browser then right click copy link
for android you can use 1DM mobile there before adding your files to download there wil be an option to copy link

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
