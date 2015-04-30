Blog plugin 0.5.1
=================
Blog for news.

How do I install this?
----------------------
1. Download and install [Yellow](https://github.com/datenstrom/yellow/).  
2. Download [blog.php](blog.php?raw=true), copy it into your `system/plugins` folder.  
3. Download [blog.html](blog.html?raw=true) and [blogpages.html](blogpages.html?raw=true), copy them into your `system/themes/templates` folder.  
4. Download [content-blog.php](content-blog.php?raw=true) and [content-blogpages.php](content-blogpages.php?raw=true), copy them into your `system/themes/snippets` folder.  
5. Download latest [language-en.ini](https://github.com/datenstrom/yellow-extensions/blob/master/languages/english/language-en.ini?raw=true) and [page-new-blog.txt](page-new-blog.txt?raw=true), copy them into your `system/config` folder.
6. Create a new folder '3-blog' in your `content` folder.
7. Add [page.txt](page.txt?raw=true) and [2013-04-07-blog-example.txt](2013-04-07-blog-example.txt?raw=true) to your `/content/3-blog` folder.

To uninstall delete the plugin files and folder.

How to use a blog?
------------------
The blog is available on your website as `http://website/blog/`. To make the blog your home page, rename the blog folder to '1-blog' and delete '1-home'. To create a new blog page, add a new file to the blog folder. Set `Published` and more settings at the top of an page. Dates should be written in the format [YYYY-MM-DD](https://github.com/datenstrom/yellow/wiki/Yellow-API#dates). Use `Tag` to group similar pages together.

Example
-------
Content file for a new blog page:

    ---
    Title: Blog page
    Published: 2013-04-07
    Author: Anna Svensson
    Tag: Example
    ---
    This is a new blog page.