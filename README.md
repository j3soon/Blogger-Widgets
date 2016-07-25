Blogger Widgets
==========

Simple and small widgets for Blogger users.

##Popular Posts Widget

When using external images in a post, the default `Popular Posts Widget` cannot show the first image as thumbnail.

This widget can fix the problem mentioned above.

This widget works well on the default template, displaying the popular posts with its first image and title. If there's no image, it only shows the title.

###How to use
1. Go to the `Layout page` of your blog.
2. In the `sidebar-right-1` block, click `Add a Gadget`.
3. In the `Basics` category, select `HTML/JavaScript`.
4. Type `Popular Posts` in the title field.
5. Copy everything in `PopularPostsWidget.html`, and paste it into the content field.
6. Press `Save` and click `Save arrangements`.
7. Done!

For people who don't know how to add a gadget, please see [Change your blog layout](https://support.google.com/blogger/answer/43708?hl=en).

###Common Problems

1. The widget is ugly.

    The appearance of this widget is very simple, using some css code can change it to your desired appearance.

2. I want to choose preferred image as thumbnail.

    Add the line below to the first line of your post, and change the `src` attribute to the preferred image.

    `<img src="thumb.png" style="display: none"/>`

3. The widget doesn't work on my blog.

    This widget works well on the default template, but there's a chance to fail in a custom template, editing its attribute can fix it. If there's still some problem, feel free to contact me.

If there's any other problem, you can contact me for further help.

###Removal

Removing this widget is very simple. 

1. Go to the `Layout page` of your blog.
2. Click `Edit` on this widget.
3. Click `Remove`.
