# 📁 Syncing SharePoint Folder with OneDrive

This guide will help you sync the SharePoint folder with your OneDrive and set up your environment for working with the Web Scraping project.

## 🔧 Prerequisites

Ensure the following are installed on your system:
- Python
- Visual Studio Code (VS Code)

If not installed, please raise a request on VIA: https://support.iqvia.com/via

## 🔗 SharePoint Folder Link

3. [Webscraping Collateral](https://quintiles.sharepoint.com/sites/CommercialEffectiveness/Shared%20Documents/Forms/AllItems.aspx?id=%2Fsites%2FCommercialEffectiveness%2FShared%20Documents%2FProjects%20%28Client%20Files%29%2FUK%20HCP%20Targeting%2F3%2E%20Webscraping%20Collateral&viewid=085c93fd%2Df41e%2D4f80%2Dbab4%2D14ad1b1cc37776b443350cbe9d&sharingv2=true&fromShare=true&at=9&CID=65d41cd7%2Dfde4%2D4c42%2Db9cd%2Dd19ee8479604&FolderCTID=0x012000755FED6782DD3B489CD8C735FF7124AE)

## 📂 Folder Contents

Inside the SharePoint folder, you will find:
- **01 Web Scraping Results**: Contains results of web scraping for different specialties (all HCP information scraped from websites).
- **02 Web Scraping Codebase**: Contains the code for all the websites.

## 🔐 Access Instructions

- If you do **not** have access to the SharePoint folder, request access from: `lakshay.j@iqvia.com`

- If you **do** have access:
  1. Click the **Sync** button on the SharePoint folder page to sync it with your OneDrive.
  2. Once synced, the folder will appear in your OneDrive directory like this:

     UploadedImage1.jpg

  3. Open this synced folder and **copy all contents** from the **02 Web Scraping Codebase** into a **separate working folder** on your system.

## 🛠️ Setup Instructions

1. Note down the path where the folder is synced to OneDrive. It will look like:
2. Open the file **Install_requirements.py** with Visual Studio Code.
3. In the terminal, run the following command to install all dependencies: 
``` python Install_requirements.py ```

4. Activate the virtual environment by running:
```   .\.venv\Scripts\activate ```
5. Run the Scraper by running the following command in the terminal:
```   streamlit run app.py ```
6. This should open a web browser requiring all the details to run the application.

## You're All Set!
You can now proceed with running the web scraping code as needed.
