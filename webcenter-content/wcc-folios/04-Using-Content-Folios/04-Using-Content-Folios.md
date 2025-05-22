# Using Content Folios

## Introduction

In this lab, you will learn about WebCenter Content Folios and content basket

**Estimated Lab Time**: *30 minutes*

### Description

Oracle WebCenter Content Server provides a quick and effective way to assemble, track, and access logical groupings of multiple content items from within the secure environment of Oracle WebCenter Content Server. For example, you can assemble all items relevant to an upcoming brochure, such as images, logos, legal disclosures, and ad copy, and send them through a workflow process. Or perhaps a new project requires a virtual place to assemble all relevant content items in a particular hierarchy, whenever they are checked in, with restricted access to particular areas of the hierarchy. Or a video may have to be associated and tracked with release waivers and narration text.

Technically, a content folio is an XML file checked in to Content Server that uses elements to define a hierarchical structure of nodes, slots, and specified content items in Content Server. In practice, a content folio is a logical grouping or a framework to structure content stored in Content Server.

A simple folio is a flat container, while an advanced folio can nest content in a hierarchy within folders. In an advanced folio, you can establish the hierarchy before, during, or after you assemble the content items.

You can add content to existing folios or lock them so changes cannot be made. You can add content items folio by searching the repository. You can add content items to an advanced folio by checking new items into the repository or by searching for existing content. An advanced folio can also contain hyperlinks to outside resources such as websites or shared network drives.

### Workshop Outline

* Provisioning WebCenter Content
* Explore Content Folios
* Use Content Basket

### Prerequisites

* Familiarity with OCI is desirable
* Familiarity with WCC is desirable

## Task 1: Create a Simple Folio

A simple folio creates a flat folio with no additional hierarchy. A simple folio displays content in a table, similar to a search results page. You can convert a simple folio to an advanced folio later if you require additional structure, however you cannot convert an advanced folio to a simple folio.

Although a simple folio displays content in a manner similar to a standard Content Server search results page, there is an important difference. A standard search results page displays content information from a content item's metadata. The Edit Simple Folio page displays element information from the XML file stored in Content Server that defines the folio. This element information is unique to the folio, and can be changed in the folio without affecting the content item's metadata

1. Login to WebCenter Content and Click on the Content Management link

2. Click New Folio.

![New Folio link](<images/New Folio.jpg>)

3. On the Pick Folio Type page, accept the default, Simple Folio.
4. Click Load folio.
5. On the Edit Simple Folio page, choose Save folio from the Actions menu.

    Note:

    You must save the folio before navigating away from it. Saving the folio checks the folio into Content Server. If you do not save the folio, it and any changes to it are lost.

6. On the Set Folio Profile page, select the profile to be used with the folio, if any, and click Next.
7. On the Folio Check In page, enter the required information and click Check in.
8. On the Folio Check In Confirmation page, select how to proceed and click Finish. Options are:
Use the Edit Folio page to continue editing the folio to add content.
Use the Content Information page to view content information for the folio.
Use the View Folio page to view the folio.

## Task 2: Create an Advanced Folio

An advanced folio is a folio that allows for a hierarchical structure. The system administrator may define the structure in a template. If the folio has no template associated with it, you can modify the folio structure dynamically as you create and edit the folio. The structure of a template-based folio may or may not be modifiable, depending on the template.

To create an advanced folio after you have logged in:

1. Click the Content Management tray.
2. Click New Folio.
3. On the Pick Folio Type page, select Advanced Folio and optionally select a template.
4. Click Load folio. If a content item associated with a selected folio template is set to be cloned, then the Set Folio Profile page opens and you are prompted to first check in the folio and skip to Step 6.
5. On the Edit Folio page, choose Save folio from the Actions menu.
    NOTE:
    You must save the page before navigating away from it. Saving the folio checks the folio into Content Server. If you do not save the folio, it and any changes to it are lost.

6. On the Set Folio Profile page, select the profile to be used with the folio, if any, and click Next.
7. On the Folio Check In page, enter the required information and click Check in.
8. On the Folio Check In Confirmation page, select how to proceed and click Finish. Options are:
Use the Edit Folio page to continue editing the folio to add content.
Use the Content Information page to view content information for the folio.
Use the View Folio page to view the folio.

## Task 3: Adding Content Items to an Advanced Folio

Content items are added to an advanced folio by using the Source Items tray on the Edit Folio page, the Element Info contextual menu, a Search Result page, or a digital asset basket. For example, content items are added to a folio by one of the following ways:

By using the Source Items area on the Edit Folio page to search for existing content, and then dragging the items into the folio hierarchy

By displaying a digital asset basket in the Source Items area on the Edit Folio page, and then dragging the items into the folio hierarchy

By choosing Insert Item by Search from the Element Info contextual menu to search for existing content and add it to the folio

By choosing Insert Item by Checkin from the Element Info contextual menu to check a new content item and add it to the folio

By using a Search Result page to add existing content to the Source Items area of a new or existing advanced folio

By publishing content gathered in a digital asset basket to a new folio created during the publishing process

Adding Items from the Source Items Area

The Source Items area of an Edit Folio page displays content checked in to Content Server. The content may be collected in a digital asset basket that is displayed in the Source Items area, or collected using the Source Items area search feature. The source items contextual menu lists each set of items that can be displayed in the Source Items area.

To add items to a folio from the Source Items area:

To collect items into the Source Items area using the search function:

1. Navigate to the Edit Folio page of the folio where you want to add content.
2. Click Search in the Source Items area.
3. On the Search for Items page, select a profile to use for searching, if any, and click Next.
4. On the search form, select the criteria appropriate to the item for which you are searching, and click Search.
5. On the Content Listing page, select the check box next to the item or items in the search results to collect, then click Next. The items are listed in the Source Items area.
From the Edit Folio page Actions menu, choose Save changes.

    Note:

    You cannot select items across multiple pages of search results.

Inserting an Existing Item Using a Contextual Menu

Items that have been checked in can be searched for and inserted directly into a folio node or slot by choosing Insert Item by Search from the Element Info contextual menu. You can also right-click the appropriate node or slot to access this contextual menu.

To search for and insert a content item directly into a folio node or slot:

1. Navigate to the Edit Folio page of the folio where you want to add content.
2. Select the node or slot into which the content goes.
3. Right-click the node or slot, or click the contextual menu in the Element Info area and choose Insert Item by Search.
4. On the Search for Item page, choose the criteria appropriate to the item for which you are searching, and click Search.
5. On the Content Listing page, click Select next to the item to insert. The item is inserted into the folio.

Inserting an New Item Using a Contextual Menu

New items that have not yet been checked in can be inserted directly into a folio node or slot by using Insert Item by Checkin in the Element Info contextual menu. You can also right-click the appropriate node or slot to access this contextual menu.

To search for and insert a content item directly into a folio node or slot:

1. Navigate to the Edit Folio page of the folio where you want to add content.
2. Select the node or slot into which the content goes.
3. Right-click the node or slot, or click the contextual menu in the Element Info area and choose Insert Item by Checkin.
4. On the Item Check In page, fill in the appropriate criteria for the item you are checking in, and click Check In.
5. On the check-in confirmation page, click Add Item to Folio. The item is inserted into the folio.
6. From the Edit Folio page Actions menu, choose Save changes.

Adding Items from a Search Result page

You can add items from a Search Result page either directly to a new folio, or to the Source Items area of an existing folio or new template-based folio. When listed in the Source Items area, content can be added to the folio by dragging it to the appropriate node or slot. For more information, see Adding Items from the Source Items Area.

To add items from a Search Result page to a new folio:

1. From a Search Result page, select the check box next to the item or items you want to add to the folio.

2. From the table Actions menu, choose Add items to folio.

3. On the Add Items to Folio page, select New folio and click Next.

4. On the Pick Folio Type page, select Simple Folio, or select Advanced Folio and choose an appropriate template, if any.

5. Selecting Simple Folio inserts the selected content items in the root node of a flat, single node folio.

6. Selecting Advanced Folio enables the Folio Template list, providing access to folio templates with structure predefined by a system administrator.

7. Click Load folio.

If you selected Simple Folio in Step 4, the Edit Simple Folio page opens with the selected elements listed. If you selected Advanced Folio in Step 4, then the Edit Folio page opens with the selected content items inserted into the root node of the advanced folio.

From the Actions menu, choose Save changes.

    Note:

    If you do not save changes before navigating away from the folio, any changes are lost.

To add items from a Search Result page to an existing folio:

1. From a Search Result page, select the check box next to the item or items you want to add to the folio.
2. From the table Actions menu, choose Add items to folio.
3. On the Add Items to Folio page, select Existing folio, and click Next.
4. On the Select Folio Profile page, select the appropriate profile, if any, and click Next.
5. On the Search for Existing Folio page, choose the criteria appropriate to the folio for which you are searching, and click Search.
6. On the Folio Listing page, click Select by the folio to which the content items are to be added.
7. On the Edit Folio page of the selected folio, drag content from the Source Items area to the appropriate node or slot. For more information, see Adding Items from the Source Items Area.
8. From the Edit Folio page Actions menu, choose Save changes.

## Task 4: Using Digital Asset Baskets

Digital asset baskets are a useful way to collect items checked in to Content Server. You add content to a digital asset basket from the Search Result page. When collected in a digital asset basket, items can be published to new folios or easily accessed from within existing folios in the Source Items tray of the Edit Folio page. You can create multiple baskets with the Manage Content Baskets page to help organize content by project, author, date, type, or any other way that you find useful.

Content added to digital asset baskets still resides in the repository. It does not change physical locations. Instead, the metadata for items in a digital asset basket updates to reflect the basket or baskets to which a content item is added. Click a digital asset basket link to execute a search for the metadata reflecting that digital asset basket, and return a search result page listing the content items. The same content can be collected in multiple baskets.

Digital asset baskets are created and deleted using the Manage Content Baskets page. You can create multiple baskets, but only one basket is active at a time. You can only add content to the active basket.

To create a digital asset basket:

1. In the My Content Server tray, click My Baskets.

2. On the Manage Content Baskets page, click Append basket. A new field is displayed on the page.

3. Enter a name for the basket in the new field.

4. Select Active next to the new basket to make it the active basket, otherwise leave disabled. Only the active basket can have content added to it.

5. Click Update. The new basket is displayed under My Baskets in the My Content Server tray.

To delete a digital asset basket:

1. Click My Baskets in the My Content Server tray.
2. On the Manage Content Baskets page, select Delete next to the basket to delete and click Update. The basket is removed from the Manage digital asset baskets page and from under My Baskets in the My Content Server tray.

Working with Digital Asset Baskets

You can create multiple digital asset baskets to help organize collected content. Only the active basket can have content added to it. Content is added to the active basket from a Search Result page. You can move content between baskets, copy content into another basket, and reorder content within a basket.

You can set the active basket on the Manage Digital Asset Baskets page.

To set the active basket:

1. Click My Baskets in the My Content Server tray.
2. On the Manage Content Baskets page, select Active next to the basket and click Update. The Basket Icon changes, and Active is displayed next to the newly active basket under My Baskets in the My Content Server tray.

Adding Content to the Active Basket

You can add content to the active basket from a Search Result page.

To add content to the active basket:

1. From a Search Result page, select the check box next to the item or items you want to add to the active basket.
2. Choose Add to active basket from the table Actions menu above the check boxes.
3. To verify that the content is added to the active basket, open My Baskets in the My Content Server tray and click the active basket icon.

Moving and Copying Content Items

If you inadvertently add content to the wrong basket and want to move it, or to reorganize your content into different baskets, you can do so. Also, you can copy content in one basket into another basket, so that it is displayed in both.

To move or copy content items from one basket to another:

1. Open My Baskets in the My Content Server tray and click the basket link of the basket from which you want to move or copy content.
2. Select the check box next to the item or items you want to move or copy.
3. Choose Move selected items or Copy selected items from the table Actions menu.
4. On the Move/Copy Basket Items page, click the basket to which the items are to be moved or copied.

Removing Content Items

You can remove items from any digital asset basket.

To remove content items from a basket:

1. Open My Baskets in the My Content Server tray and click the basket link of the basket from which you want to remove content.
2. Select the check box next to the item or items to remove.
3. Choose Remove selected items from the Actions menu.

## Task 5: Finding Existing Folios

Locking and Unlocking Folios

Locking a folio takes a snapshot of a folio and locks it, preventing it from being edited. After a folio is locked, people who have rights to edit the folio are directed to the View Folio page instead of the Edit Folio page.

To lock a folio:

1. Navigate to the Edit Folio page of the folio.

2. Choose Lock folio from the Actions menu.

If required, you can unlock a locked folio for additional edits. Unlocking a folio duplicates the locked folios hierarchy as a new revision available for editing.

To unlock a folio:

1. Navigate to the Edit Folio page of the folio.
2. Choose Create editable revision from the Actions menu.

Downloading Folio Renditions

Your system administrator defines renditions and can make them available in a variety of forms. For example, a single ZIP file rendition could contain all folio content to which you have access. A PDF rendition could assemble all folio content to which you have access into a single PDF file suitable for printing.

To download renditions of a folio:

1. Navigate to the Edit Folio page of the folio.
2. Choose the rendition you require from the Renderers menu.
3. In the dialog box, specify the location for the download.

    Note:

    A PDF rendition is only possible if the content associated with the folio has a PDF Web-viewable file. That is, either the associated content item is a PDF file, or that your system administrator has set up PDF Converter to generate a PDF version.

    Note:

    Only folio items that have a PDF version become part of the PDF rendition.

Finding Existing Folios

Because Content Server manages a folio as a single XML file, you can find folios by searching Content Server in the same way you would find any content item. You can use the search tray, the Advanced Search page, or the Quick Search field to search for folio titles or other associated metadata. Only folios for which you have permissions are displayed in the search results. A folio icon is displayed in the Actions column of the search results field. Click the icon to display the folio. If you can edit the folio, the Edit Folio page opens, otherwise, the View Folio page opens.

On the content info page of a content item that is in a folio, there is a Folio Membership section (above the Revision table) with a show link which lists the folios to which the content is a member. There are also action icons next to the listed folios with the option to View the Folio or see it's content info.

Viewing Folios

You can view Folios in the following ways:

The Edit Folio page displays the folio hierarchy and allows you to edit the folio, provided you have the rights to do so.

The View Folio page shows, by default, the folio hierarchy but does not allow you to edit it. Your system administrator can define additional views that may not resemble the default folder hierarchy view.

View the native XML file (file extension .xcsr) from a content information page link.

Viewing Folio Information

Folio information, including revision history, is displayed on the content information page of the XML file checked in to Content Server. To access folio information, click the Info icon next to a folio in the Actions column on a Search Result page, or choose Content Item info from the Actions menu on the Edit Simple Folio page, Edit Folio page, or View Folio page.

Subscribing to Folios

You can subscribe to simple and advanced folios like any other item in Content Server. Because changes can be made to folios and folio items without causing a new revision to the folio, however, you can choose the types of changes that cause you to be notified using the Subscribe to folio_name page.

To subscribe to changes made to a folio or folio items:

1. Choose Subscribe from the Content Actions menu on the content information page of the folio to which you want to subscribe.
2. On the Subscribe to folio_name page, select the check box next to one or more of the actions for which to be notified:
3. Click Subscribe. The standard content information page for the folio opens.

## Acknowledgements

* **Authors-** Cordell Melgaard, Advanced Principal Support Engineer Oracle WebCenter Content

* **Last Updated By/Date-** Cordell Melgaard May 2025
