---
title: Home
---

# True Life Church
## An Apestolical Church of Jeseus Christ


!!! If you want a more **full-featured** base install, you should check out [**Skeleton** packages available in the downloads](http://getgrav.org/downloads).
<p align="center">
#### Our Pastuers 

* Pastor - John Bower 
* Assitant Pastor - Robert Thomas

#### Our Services 

*Sunday Bible Study - 10:00 AM to 11:00 AM

*Sunday Service - 11:00 AM to 12:00 PM

*Wednesday Bible Study - 7:30 PM - 8:30 PM

#### Curch Contact Information

222222 Chula Road 
Amelia, VA 23002

(804) 561 - 2222

</p>

Creating a new page is a simple affair in **Grav**.  Simply follow these simple steps:

1. Navigate to your pages folder: `user/pages/` and create a new folder.  In this example, we will use [explicit default ordering](http://learn.getgrav.org/content/content-pages) and call the folder `02.mypage`.
2. Launch your text editor and paste in the following sample code:

        ---
        title: My New Page
        ---
        # My New Page!

        This is the body of **my new page** and I can easily use _Markdown_ syntax here.

3. Save this file in the `user/pages/02.mypage/` folder as `default.md`. This will tell **Grav** to render the page using the **default** template.
4. That is it! Reload your browser to see your new page in the menu.

! NOTE: The page will automatically show up in the Menu after the "Home" menu item. If you wish to change the name that shows up in the Menu, simple add: `menu: My Page` between the dashes in the page content. This is called the YAML front matter, and it is where you configure page-specific options.
