[Facebook Comments for PencilBlue](http://pencilblue.org)
=====

##### Add Facebook comments to your articles

Installation and Setup
-----

1. Clone the fbcomments-pencilblue repository into the plugins folder of your PencilBlue installation
```shell
cd [pencilblue_directory]/plugins
git clone https://github.com/pencilblue/fbcomments-pencilblue.git
```

2. Install the fbcomments-pencilblue plugin through the manage plugins screen in the admin section (/admin/plugins).

3. Go to the fbcomments-pencilblue settings screen (/admin/plugins/settings/fbcomments-pencilblue) and set your Facebook app ID. An app ID isn't necessary, but without one, Facebook will trigger JavaScript console warnings.

4. Add a ```^tmp_fb_root^``` directive to the top of pages that you want the comments to appear in (preferably right after the opening body tag in your head template).

5. Add the ```^tmp_fb_comments^``` directive in your article template where you want the comments to appear.
