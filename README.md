# open_charity_theme
open charity drupal7 theme

##demo site
[open charity](http://yan-dong.com)

## Administrator account:
username: admin
password: 123456
admin login: [user login](http://yan-dong.com/user)
admin page : [admin page](http://yan-dong.com/admin)

## Explanation

- If you want to change banner image and text, go to **Structure > Blocks**, select "banner image and text" block configure, this block has been created and assigned to "Banner" region.
- "Next event" view block was created and assigned to "Event" region to show latest event, if you want to add a new event, got to **Content > Add content > Article**, create a new article which contain a "event" tag.
- "Blogs" view block was created and assigned to "Blogs" region to show all published blogs.

-- In order to implement the paging arrow of blogs, I use css to hide the default pager elements of the Blogs view, and use javascript binding two click events to the paging arrow (actually bind to body element), when paging arrow was clicked, trigger the default previous and next click event on default pager elements.
