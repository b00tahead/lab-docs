---
id: content-types
title: Content Types
sidebar_label: Content Types
---

In this section, we will cover how to create content for each of the main content types:

* Static pages
* News
* Directory entries
* Home Sliders

There are other content types available but as of now the current theme does not support those content types.

## Content Types

### Static Page
Static pages will most likely make up the majority of content on your website. Pages of this content type can be used for many purposes but it is best to use this content type for pages that will not change much (hence the term “static” page).

> In order to create a new static page you can use the administration menu and go to **Content > Add content > Static page**.

Static pages contain the following fields:

* Title (required): This will be the heading displayed above the page
* Content: Here you can rearrange the order paragraphs are displayed on the page
* [Paragraph type](paragraphs.md): You can add as many paragraphs as needed.
* [Extra settings](contenttypes.md#extra-settings): These page options will be discussed in a separate section

When the content is ready, you can save the page using the button at the bottom of the page.

### News
The News content type can be used for updates, upcoming events, and press mentions. Content published using this content type will automatically populate the `View: News` block as well as the `/news` page.

> In order to create a news page you can use the administration menu and go to **Content > Add content > News**.

News content contain the following fields:

* Title: The page heading displayed above the content
* Feature Image: Used to display a full-width image at the top of the content
* Feature Copy: A brief summary of the news item or posting. The text entered here will be displayed on both the `View: News` block as well as the `/news` page.
* Body: The actual content of the news item. You can rearrange the order in which content appears.
* [Paragraph type](paragraphs.md): You can add as many paragraphs as needed.
* [Extra settings](contenttypes.md#extra-settings): These page options will be discussed in a separate section

When the content is ready, you can save the page using the button at the bottom of the page.

### Directory Entry
Site administrators can create directory entries in order to populate the `/directory` page with members of their lab, team, or organization. These entries can optionally be categorized with the use of tags.

> In order to create a news page you can use the administration menu and go to **Content > Add content > Directory entry**.

Directory entries contain the following fields:

* Name: The name to be displayed on the directory and profile page
* Last Name: The individual’s last name (used for sorting)
* Title: The job title or responsibility of the individual (Ex. Professor, Research Assistant, Treasurer)
* Email Address & Phone Number: Contact information for the individual
* Headshot: Photo displayed on the directory and profile page
* Web Profile Link: Links to any relevant sites, articles, or pages. Site administrators can enter text in the _Title_ field as display text for the URL
* Directory Info: The order of content 
* [Paragraph type](paragraphs.md): You can add as many paragraphs as needed.
* Category: Use this field to select a category in which an individual belongs
* [Extra settings](contenttypes.md#extra-settings): These page options will be discussed in a separate section

When the content is ready, you can save the page using the button at the bottom of the page.

### Home Slider
Content created for the Home Slider content type will be automatically added to the `Home: Slider` view. This view will show the five most recent sliders sorted by date created. Keep in mind that sliders will automatically be cropped to 1600px by 500px.

> To create a slider you can use the administration menu and go to **Content > Add content > Home Slider**.

Sliders contain the following fields:

* Title: Only used to help identify the content
* Slider Image: Image to be displayed
* Slider Text: Text to be displayed on the slider. Text can include links.
* Text Location: Not currently supported by the theme.
* [Extra settings](contenttypes.md#extra-settings): These page options will be discussed in a separate section

When the content is ready, you can save the page using the button at the bottom of the page.

### Other Content Types
The following content types are visible and able to be used, but they are not supported by the current theme:

* Article
* Publication
* Webform

Support may be added for them in the future. If there is a content type you think would be useful, [submit a request](request.md).

## Extra Settings
### Menu settings
This section allows a page to be added as a menu link. [Menus](menu.md) are covered in a different section.

### Revision information
Check _Create a new revision_ and add a _Revision log_ message if you would like to include an explanation of the changes made.

### URL path settings
URL paths are automatically generated but if you would like to create a custom URL path you can uncheck _Generate automatic URL alias_ and enter the alternative URL in the _URL alias_ field.

### Authoring information
Authoring information is automatically generated based on the user who created the content and the time and date the content was created.

### Publishing options
Publishing options determine if content is visible on the site. If you wish to hide content from the website you can simply uncheck _Published_.

## Editing Content
Site administrators can easily find and update content that has already been created.

> To view the list of all content on the site click **Content** on the administration menu.

From this screen, site administrators can filter, sort, and apply bulk updates to content.

### Filtering Content
Site administrators are able to filter all content by its status and content type. Once the criteria has been selected, apply the filter by clicking **Filter**.

### Editing Content
To edit a single item, find the content item you’d like to update and click **edit** under the _Operations_ column.

### Deleting Content
To delete a single item, find the content item you’d like to update and click **delete** under the _Operations_ column.

### Bulk Updates
Site administrators can also update multiple items at one time. Just check each item that needs to be updated and then select the desired operation from the _Update Options_ dropdown. Once an option has been selected, click **Update** to apply the operation to all selected items.
