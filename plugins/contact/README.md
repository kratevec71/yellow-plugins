Contact plugin 0.5.1
======================
Email contact page for website.

How do I install this?
----------------------
1. Download and install [Yellow](https://github.com/datenstrom/yellow/).  
2. Download [contact.php](contact.php?raw=true), copy it into your `system/plugins` folder.  
3. Download [contact.html](contact.html?raw=true), copy it into your `system/themes/templates` folder.  
4. Download [content-contact.php](content-contact.php?raw=true), copy it into your `system/themes/snippets` folder.  
5. Download latest [language-en.ini](https://github.com/datenstrom/yellow-extensions/blob/master/languages/english/language-en.ini?raw=true), copy it into your `system/config` folder.
6. Create a new folder 'contact' in your `content` folder.
7. Add [page.txt](page.txt?raw=true) to your `content/contact` folder.

To uninstall delete the plugin files and folder.

How to use a contact page?
--------------------------
The contact page is available on your website as `http://website/contact/`. You can add a link to your navigation or individual pages. Your email address can be defined in the settings at the top of a contact page, for example `ContactEmail: user@user.com`. A global email address can be defined in the main configuration. There's a spam filter to block unwanted advertising.

**Important**: This plugin does not work with static websites, it needs a Yellow installation.