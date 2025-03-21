---
title: Add SharePoint as a learning content source for Microsoft Viva Learning
ms.author: daisyfeller
author: daisyfell
manager: pamgreen
ms.reviewer: chrisarnoldmsft
ms.date: 10/27/2021
audience: admin
ms.topic: article
ms.service: 
ms.prod: microsoft-365-enterprise
search.appverid: MET150
ms.collection: 
    - enabler-strategic
    - m365initiative-viva-learning
localization_priority: medium
description: Learn how to add SharePoint as a learning content source for Microsoft Viva Learning.

---

# Add SharePoint as a content source for Microsoft Viva Learning

You can configure SharePoint as a learning content source to make your organization's own content available in Viva Learning.

>[!NOTE]
> Content accessible through Viva Learning is subject to terms other than the Microsoft Product Terms. Any content you add to Viva Learning, such as SharePoint-hosted content, is subject to the privacy and service terms associated with that content.

## Overview

The knowledge admin (or global administrator) provides a site URL to where the [Learning Service](configure-sharepoint-content-source.md#learning-service) can create an empty centralized location in the form of a structured SharePoint list. This list is called the Learning App Content Repository. Your organization can use this list to house links to cross-company SharePoint folders that contain learning content. Admins are responsible for collecting and curating a list of URLs for folders. These folders should only include content that can be made available in Viva Learning.

Viva Learning supports the following document types:

- Word, PowerPoint, Excel, PDF
- Audio (.m4a)
- Video (.mov, .mp4, .avi)

For more information, see [SharePoint limits](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-limits?redirectSourcePath=%252farticle%252fSharePoint-Online-limits-8f34ff47-b749-408b-abc0-b605e1f6d498).

## Multi-geo

If you're using [Microsoft 365 Multi-geo](/microsoft-365/enterprise/microsoft-365-multi-geo), the site URL provided by the knowledge admin (where the Learning App Content Repository will be located) needs to belong to the central location where your Microsoft 365 subscription was originally provisioned. Folders linked to in the repository should also belong to the central location. Viva Learning has added this restriction to conform to data residency requirements.

[Microsoft 365 Multi-geo](/microsoft-365/enterprise/microsoft-365-multi-geo) is designed to meet data residency requirements. For more information, see [Multi-geo capabilities in SharePoint Online](/microsoft-365/enterprise/multi-geo-capabilities-in-onedrive-and-sharepoint-online-in-microsoft-365).

## Permissions

Document library folder URLs can be collected from any SharePoint site in the organization. Viva Learning follows all existing content permissions. Therefore, only content for which a user has permission to access is searchable and visible within Viva Learning. Any content within these folders will be searchable, but only content to which the individual employee has permissions can be used.

Content deletion from your organization's repository is not currently supported.

To remove unintentionally surfaced content, follow these steps:

1. To restrict access to the document library, select the **Show actions** option, and then select **Manage access**.

     ![Document library page in SharePoint showing Show actions option with Manage access highlighted.](../media/learning/learning-sharepoint-permissions2.png)

2. Delete the original document within the document library.

For more information, see [Sharing and permissions in the SharePoint modern experience](/sharepoint/modern-experience-sharing-permissions).

## Learning Service

The Learning Service uses the provided folder URLs to get metadata from all content stored in those folders. Within 24 hours of supplying the folder URL in the centralized repository, employees can search for and use your organization's content within Viva Learning. All changes to content, including updated metadata and permissions, will also be applied in the Learning Service within 24 hours.

## Configure SharePoint as a source

You must be a Microsoft 365 global administrator, SharePoint administrator, or knowledge admin to perform these tasks.

To configure SharePoint as a learning content sources in for Viva Learning, follow these steps:

1. In the left navigation of the Microsoft 365 admin center, go to **Settings** > **Org settings**.

2. On the **Org settings** page, on the **Services** tab, select **Viva Learning**.

     ![Settings page in the Microsoft 365 admin center showing Viva Learning listed.](../media/learning/clcs-services.png)

3. On the **Viva Learning** panel, under SharePoint, provide the site URL to the SharePoint site where you want Viva Learning to create a centralized repository. If your SharePoint site is new, you'll need to wait 1 hour after site creation to add it here.

     ![Learning panel in the Microsoft 365 admin center showing SharePoint selected.](../media/learning/sharepoint-1.png)

     If your organization uses [Microsoft 365 Multi-geo](/microsoft-365/enterprise/microsoft-365-multi-geo), you can find your region or country at [Microsoft 365 Multi-geo availability](/microsoft-365/enterprise/microsoft-365-multi-geo#microsoft-365-multi-geo-availability). The **Viva Learning** panel also shows this information.

     ![Learning panel in the Microsoft 365 admin center showing a message that the SharePoint URL must be in the central location.](../media/learning/sharepoint-2.png)

4. A SharePoint list is created automatically within the provided SharePoint site.

     In the left navigation of the SharePoint site, select **Site contents** > **Learning App Content Repository**.

     ![SharePoint list showing the Site contents navigation and the Learning App Content Repository section.](../media/learning/learning-sharepoint-configure4.png)

5. On the **Learning App Content Repository** page, populate the SharePoint list with URLs to the learning content folders.

   1. Select **New** to view the **New item** panel.

       ![Learning Content Repository page in SharePoint showing the New option.](../media/learning/learning-sharepoint-configure5.png)

   2. On the **New item** panel, in the **Title** field, add a directory name of your choice. In the **Folder URL** field, add the URL to the learning content folder. Select **Save**. [Learn how to to create the folder URL](#folder-url-document-library-curation).

       ![New item panel in SharePoint showing the Title and Folder URL fields.](../media/learning/learning-sharepoint-configure6.png)

   3. The **Learning App Content Repository** page is updated with the new learning content.

       ![Learning Content Repository page in SharePoint showing the updated information.](../media/learning/learning-sharepoint-configure7.png)

   4. If your organization uses [Microsoft 365 Multi-geo](/microsoft-365/enterprise/microsoft-365-multi-geo) and you try to add a link to a folder that doesn't belong to the central location, you'll get an error message. All folders need to belong to the central location.
       ![Error message in the New item panel saying that all uploaded folders need to be in the central location.](../media/learning/learning-sharepoint-configure-geo2.png)

  > [!NOTE]
  > To allow for broader access to the Learning App Content Repository, a link to the list soon will be available in the Viva Learning interface where users can request access and ultimately help populate the list. Site owners and global administrators will be required to grant access to the list. Access is specific to the list only and does not apply to the site where the list is stored. For more information, see [Provide your own organization's content](#provide-your-own-organizations-content) later in this article.

### Folder URL document library curation

Create a folder to store learning content for your organization.

1. Go to your Documents library and select **+ New**.

    ![Image of an empty documents library with the cursor selecting New and Folder.](../media/learning/spfolder-3.png)

2. Choose **Folder** and enter a folder name.

    ![Image of the Create a folder pane with the name Training Materials entered.](../media/learning/spfolder-5.png)

3. Select **Create**. The folder will now show up in your document library.

    ![Image of a folder called Training Materials in the document library.](../media/learning/spfolder-6.png)

4. Upload files that you want to publish as learning content in this folder.
5. To get the folder url, choose this folder and select **Copy link**.

    ![Image of the Link copied popup.](../media/learning/spfolder-8.png)

Default metadata (such as modified date, created by, document name, content type, and organization name) is automatically pulled into Viva Learning by the Microsoft Graph API.

To improve overall discovery and search relevance of the content, we recommend adding a **Description** column. If there's already a description column present, you can delete it and add a new one by following the steps below.

To add a **Description** column to the document library page, follow these steps:

1. On the **Documents** page, select **Add column**.

2. Select the **Show actions** option, and then select **Single line of text**.

    :::image type="content" alt-text="Documents page in SharePoint showing the Show actions options with Single line of text highlighted." source="../media/learning/learning-sharepoint-curation1.png":::

3. On the **Create a column** panel, in the **Name** field, add a descriptive name for the column. Select **Save**.

    ![Create a column panel in SharePoint showing the Name and other fields.](../media/learning/learning-sharepoint-curation2.png)

4. On the **Documents** page, in the **Description** column, add custom descriptions for each item. If no description is supplied, Viva Learning will provide a default message that highlights the content as being from your own SharePoint library.

     ![Documents page in SharePoint showing the descriptions in the Description column.](../media/learning/learning-sharepoint-curation3.png)

### Provide your own organization's content

Knowledge admins can access their organization's Learning App Content Repository in SharePoint, where they can provide references to cross-organization document libraries. Content within these libraries will be then surfaced as learning content in Viva Learning.

1. In Viva Learning, select the ellipses (**...**), and then select **Settings**.

    ![SharePoint library page showing the More options and Settings option.](../media/learning/sharepoint-3.png)
  
2. Under **Settings**, select **Permissions**.

    ![Settings option page in SharePoint showing the Permissions and Check access options.](../media/learning/learning-sharepoint-library-2.png)

3. Select **Check access** to connect to your organization's centralized library.

## Next step

[Add learning management systems for Viva Learning](configure-lms.md) or [Add other content providers for Microsoft Viva Learning](configure-other-content-sources.md).
