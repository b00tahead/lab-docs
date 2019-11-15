---
id: blocks
title: Blocks
sidebar_label: Blocks
---

Blocks are small chunks of information that can be displayed in different regions on the website. Blocks can be static HTML or text, menus, or the dynamic output of content from views. A single block is able to placed within any region, but, as we’ll cover in the following sections, in order to maintain a coherent look and feel there are regions that should only contain certain blocks formatted for those regions.

## Block regions
> You can reach the block regions page from the administration menu by selecting **Structure > Blocks**.

### Demonstrate block regions
Clicking on the **Demonstrate block regions** link will show you an example layout of the different block regions available on the website. Not all regions will be displayed on this screen, as some regions are only visible to the front page of the site.

### Home: Slider
The _Home: Slider_ region is only visible on the front page of the website. This region is where the `Home: Slider` block should be placed.

> It is strongly advised not to place any other blocks in this region.

The `Home: Slider` block will display the last 5 items with a content type of _Home Slider_.

### Home: Content
The _Home: Content_ region was designed to allow site administrators to add custom content. You can create blocks that embed images, video, HTML, or just plain text and add it to this region. The _Home: Content_ region will only display on the front page of the website. It is recommended to use this region to add content such as (but not limited to):

* a mission statement
* a brief description of the lab, organization, or purpose of the site
* any other introductory material

### Home: News
The _Home: News_ region is the last region that is only displayed on the front page. This region will contain the `View: News` block which shows the three most recent published news items.

> It is strongly advised not to place any other blocks in this region.

### Sidebar
The _Sidebar_ region can be displayed on any page except the front page. Any blocks placed here will show up to the left of the main content. While you can add any custom blocks or content and place it here we will show later in the guides how to create a sidebar menu block that will allow users to more easily navigate throughout the site.

### Content
This region is where the main content for pages of any content type will be located. Do not remove the `Main page content` block from this region. You can add any extra custom blocks to this region either above or below the `Main page content` block if you choose.

### Footer
The _Footer_ region is designed for site administrators to add any extra information they feel is necessary. This could be contact information, links to pages on the site or to other sites, or other content.

> This region works best if you limit the number of blocks to four total.

### Disabled
This region includes all blocks that you do not want displayed on the site. Any block moved here will not appear anywhere on the site.

## Creating a custom block
In order to create your own custom block you can navigate to the Blocks page from the administration menu.

> Go to **Structure > Blocks**.

From the _Blocks_ page you can select **Add block** and it will bring up the new custom block page.

### Block title
This field is optional. If you include a title it will be displayed above the block once it is placed in a region. If you would like to hide the title, you can enter `<none>` into this field.

### Block description
The block description field is used so that you can easily find this block from the _Blocks_ page. It will not show up for users of the website.

### Block body
You can add any custom HTML, text, or images to the text editor.

### Region Settings
You can skip this setting for now.

### Visibility Settings
The visibility settings allow site administrators to either hide or show blocks depending on the current page, content type, roles, or users.

#### Pages
There are two options for showing blocks on specific pages. If you would like the block to show on most pages but be hidden on only a few pages, you can select the option for _All pages except those listed_. Then you can enter in the pages (each on a separate line) on which you would like the block to not appear. The format for specifying a page is to include the relative path of a page. Some example include `news` and `news/*` for each individual news item.

If you would like the block to only appear on a few pages, you can select the option for _Only the listed pages_ and add those pages in as stated above.

#### Content types
If you would like a block to only appear for a specific content type you can select them from this list. For example, if you created a custom block to show recent news items, you could choose to display that block only for pages with the _News_ content type.

#### Roles
Similarly to the content types setting, here you can specify a block to only appear for certain user roles. A common example is to only display the user login block to anonymous users and hide it for everyone else since they will already be logged in.

#### Users
This setting can allow users to set their own visibility settings for that block.

> It is strongly advised to not change this setting.
