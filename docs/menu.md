---
id: menu
title: Menu
sidebar_label: Menu
---

There are a couple different ways to add links to the primary navigation menu. These links will also be useful for creating menu blocks that can be added in the sidebar region. Take a look at this guide for more information.

## Add a link to the main menu from the menu screen
To get to the menu screen, navigate to Structure > Menus > Main menu from the administration menu. These are the links that make up the primary navigation menu. There are two kinds of menu items you can add. A top-level (or parent) link is a menu item that will appear on the primary navigation bar and could contain zero or more sub-level links. A sub-level (or child) link will have a parent link. 

### Adding a new top-level (parent) menu item
To add a new link, click Add link. Enter the Menu link title and the link Path*. Leave the Enabled field if you would like the menu to be active. Check Show as expanded if this is a parent link with one or more child links. This allows the menu dropdown to expand when a user hovers over the parent link. Leave Parent link set to `<Main menu>`.

### Adding a new sub-level (child) menu item
To add a new child link, click Add link. Enter the Menu link title and the link Path*. Leave the Enabled field if you would like the menu to be active. To choose a parent link, click the Parent link dropdown and select the parent link from the <Main menu> section. For example, to add a Mission & Values link underneath the About link, you would select About as the parent link.

### *Note on Link Paths
For the Path field, there are three types of links you can use: internal links, external links, and a link to the home page.

Internal links are relative URLs which means you don’t need the full website address. For example, if the full URL for the about page is https://example.engr.uky.edu/about, you only need to type about (no leading slash) into the Path field. 

External links need to be entered as a complete web address. If you want to link to another website you will enter http://example.com into the Path field.

The final type of link path (which site administrators shouldn’t need to use) uses a shorthand expression <front> which will link to the front page of the website.

## Add a link to the main menu from a created page
Site administrators can also specify a menu link once they have created a new page. At the bottom of the page are a set of additional page settings that an administrator can update. One such setting is the Menu settings section. You can create a menu link by selecting Provide a menu link. This will bring up some additional settings. Enter in the text for the menu link. If you want the menu item to show up on the primary navigation menu, leave Parent item as <Main menu>. If this link is a sub-level link of another link, you can select that link from the Parent item dropdown menu.

## Rearrange menu items
At any time, site administrators can change the order that links appear in the menu. Using the administration menu, navigate to Structure > Menus > Main menu. From this screen you can drag links using the plus-shaped handle to the left of the link name. You can drag links up and down as well as nesting a link under another menu item. Once you have rearranged the menu items, click Save configuration.
