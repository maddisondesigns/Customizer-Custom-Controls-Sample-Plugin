# Customizer Custom Controls Sample Plugin #

**Author:** Anthony Hortin  
**Author URI:** https://maddisondesigns.com  
**License:** GNU General Public License v2 or later  
**License URI:** http://www.gnu.org/licenses/gpl-2.0.html  
**Version:** 1.2.1

This is a sample plugin to show how to implement my Customizer Custom Controls (and the core default controls). My Customizer Controls can be found at [https://github.com/maddisondesigns/customizer-custom-controls](https://github.com/maddisondesigns/customizer-custom-controls).

This example plugin shows how to incorporate Customizer functionality into your plugin, including examples of how to create Panels, Sections and how to update the Live Preview window. As well as showing the usage of the (built-in) core controls, there are also a number of Custom Controls, the details of which can be found in the abovementioned repo.

The example code in /inc/customizer.php will:  

- Creates a new Panel in the Customizer called **Header & Navigation** which contains three sections (Social Icons, Contact & Search).  
- Creates a new section called **Sample Custom Controls** which contains examples of all the custom controls I created.  
- Creates a new section called **Default Controls** which contains examples of all the core controls that are included in WordPress.  
- Creates a new section called **WooCommerce Layout** with sample controls if the WooCommerce plugin is activated

## Installation ##

1. Upload the 'simple-custom-controls' folder to your '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to the 'Appearance > Widgets' screen and insert the 'Simple Inline SVG' widget into one of your sidebars

## Further Reading ##

If you'd like to learn more about Customizer development, you can check out the links to my Customizer Developer's Guide, below.  
[The WordPress Customizer – A Developers Guide (Part 1)](https://maddisondesigns.com/2017/05/the-wordpress-customizer-a-developers-guide-part-1)  
[The WordPress Customizer – A Developers Guide (Part 2)](https://maddisondesigns.com/2017/05/the-wordpress-customizer-a-developers-guide-part-2)

## Changelog ##

= 1.2.1 =
- Updated plugin with latest version of Customizer code (1.3.1)

= 1.2.0 =
- Updated plugin with latest version of Customizer code (1.3.0) which includes new Divider Control
- Updated Font Awesome to v6.4.0
- Added 500px, Artstation, Figma, Mastodon (works with mastodon.social & mastodon.art), Quora, Steam, Telegram, TikTok, Unity, Unsplash & WhatsApp social icons
- Added skyrocket_social_icons_plurality filter to change the plurality of the social icons (e.g. Use it to change 'Follow me on...', to 'Follow CompanyName on...')

= 1.1.0 =  
- Updated plugin with latest version of Customizer code (1.2.1)

= 1.0.0 =
- Initial release.
