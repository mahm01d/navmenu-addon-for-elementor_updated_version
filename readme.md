# NavMenu Addon For Elementor #

**main developers:** [themeisle](https://profiles.wordpress.org/themeisle), [codeinwp](https://profiles.wordpress.org/codeinwp)  
**updated by:** [mahm01d](https://linkedin.com/in/mahm01d)
**Tags:** elementor, pagebuilder, page builder, page builder menu, page builder navmenu, menu builder, builder navigation menus, navigation, menus, navmenu, nav menu    
  
works fine on elementor higher than 3.6 
  
  **Requires PHP:** 7.4    
**Requires at least:** 4.4    
**Tested on wordpress up to:** 6.2.2  
**License:** GPLv3  
**License URI:** https://www.gnu.org/licenses/gpl-3.0.html     

Adds new NavMenus to the Elementor Page Builder plugin. Now with Site Branding options

## Description ##
Custom WordPress navmenu specifically designed for the [Elementor Page Builder](https://wordpress.org/plugins/elementor/) - Now with Site Branding options, search box, basic MegaMenu and Fullscreen Menu Overlay

## Installation ##
* These instructions assumes you already have a WordPress site and the Elementor plugin installed and activated. Also, it is assumed that you already have at least a menu created.

1. Install using the WordPress built-in Plugin installer, or Extract the zip file and drop the contents in the `wp-content/plugins/` directory of your WordPress installation.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to Pages > Add New
4. While in the Elementor Editor, drag and drop the NavMenu widget to the location of your choice
4. Configure as desired and save.
5. Done! Enjoy :)

## Frequently Asked Questions ##

**I've added the menu element but I do not see the menus in the dropdown box**    

Make sure that you have created your menus under Appearance >> Menus

**In the Branding module, I've selected the logo but it does not appear**    

Make sure a) your theme supports the custom logo options and b) that a logo has been set in the theme's customizer.   

**How do I make a split navigation with the Site title/logo in the middle?**

a: Go to Appearance >> Menus (if not already done so) and create two sets of menus - for brevity will call them Left Menu and Right Menu   
b: Go to create a page (if not already done so), give it a title say Navigation Bar 1 and click Edit with Elementor. It is recommended to use a blank template for this - if your theme does not have you can use the Page Template plugin.   
c: In the Edit mode insert a 3 column section into the page, adjust the middle column to be slight narrower than the 2 outer ones.   
e: Drag and drop the NavMenu widget in to each of the outer columns and adjust setting as desired. Now drag and drop the Branding element into the middle column - adjust settings accordingly and save.   
Done! :)  

## Screenshots ##

1. Header With Twin Navigation.
2. Fullscreen Overlay Menu
3. MegaMenu Structure On the Menu edit screen.
4. MegaMenu Frontend

## Known Issues ##

* Currently both the Overlay and MegaMenu content are not viewable while in Edit Mode - this is due to both having an on.Click event to display content which does not seem to work in the Editor.
* For the time being, any changes made to both of the above can be viewed on the frontend of the site. A fix is being sought and will be implemented as soon as a viable solution is found!

## Changelog ##
### 2023-05-22  ### 
* Fixed issues after updating/upgrading the elmentor plugin to 3.6 or higher caused due to debrecated functions still not updated 
the new functions replaced as mentioned in 
https://developers.elementor.com/v3-6-planned-deprecations/ 

