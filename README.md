# Notero Literature Review
A guide to using Notion and Zotero for a literature review. *Adapted from https://www.nature.com/articles/d41586-022-01878-7*

## Installation Guide
### Set Up
**_Step One_**: Install [Zotero](https://www.zotero.org/download/) (if you have not done so already)

**_Step Two_**: Create a [Notion](https://www.notion.so/) Account

**_Step Three_**: Duplicate [Notion Template](https://ordinary-medicine-af6.notion.site/b51ba13dcb51435cb0fc3d6d69592b7b?v=d4483d14e59f46459f7948f067aeda70). Feel free to rename it to something else once you have duplicated it.

**_Step Four_**: Download the .xpi [File](https://github.com/dvanoni/notero/releases/tag/v0.4.6)

<p align="center">
  <img src="https://github.com/IRSS-UBC/NoteroLiteratureReview/blob/main/images/xpi_img.png">
</p>

### Configure Notion
**_Step One_**: Create an [Internal Integration](https://www.notion.com/my-integrations) in Notion.

<p align="center">
  <img src="https://github.com/IRSS-UBC/NoteroLiteratureReview/blob/main/images/notion_integrations.png" width=50% height=50%>
</p>

  * Name it something you will remember (i.e. Zotero) and make sure that the Associated Workspace is correct.

<p align="center">
  <img src="https://github.com/IRSS-UBC/NoteroLiteratureReview/blob/main/images/create_integration.png" width=50% height=50%>
</p>

  * Show the generated secret and copy and paste it somewhere to use later

<p align="center">
  <img src="https://github.com/IRSS-UBC/NoteroLiteratureReview/blob/main/images/copy_secret.png" width=50% height=50%>
</p>

**_Step Two_**: Share the Notion Template With the Integration.
  * Go to the Literature Review Template that you duplicated to your Notion workspace
  * Click on the **...** at the top right corner of the page
  * Click **Add connections**
  * Find and select the correct integration (i.e. what ever you named it) using the **Search for connections...** menu

<p align="center">
  <img src="https://github.com/IRSS-UBC/NoteroLiteratureReview/blob/main/images/share_integration.png">
</p>

**_Step Three_**: Copy and Paste Database ID Somewhere
  * The database ID is a string of 32 characters in the database URL that is between the slash following the your workspace name and the question mark (?)

<p align="center">
  <img src="https://github.com/IRSS-UBC/NoteroLiteratureReview/blob/main/images/database_id.png">
</p>

### Install/Configure Notero Plugin
**_Step One_**: Open Zotero Add-ons Manager - **Tools &#8594; Add-ons**
