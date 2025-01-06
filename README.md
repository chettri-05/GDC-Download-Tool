# GDC-Download-Tool
1.Visit the GDC Portal and log in to your account.
2.Navigate to the files or dataset of interest, subset them as needed, and add them to the cart.
3.Once your selection is complete, click on the "Download Manifest" button in the cart.
4.Save the downloaded manifest.txt file to your computer. It’s recommended to place this file in the same folder where the GDC Data Transfer Tool will be installed for easier access.
5.Download the GDC Data Transfer Tool client from the GDC website. Choose the appropriate version for your system (e.g., Windows, MacOS, Linux).
For Windows users, download either:
Command-Line Tool: gdc-client_2.3.0_Windows_x64-py3.8-windows-2019.
UI-Based Tool: gdc_dtt-ui_v1.0.0_win_x64.zip.
6.Open the folder where the GDC Data Transfer Tool is located.
7.Use the following command to download data:

gdc-client download -m manifest.txt -d "path_to_download_directory"

8.Once the download completes, navigate to the output directory specified during the download process.
Confirm that all the files listed in the manifest file have been downloaded
9.
