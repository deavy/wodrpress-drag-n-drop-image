Drag & Drop Image Plugin for Wordpress
===========================

Drag & Drop Image is a plugin made to save you time when inserting an image into post in Wordpress. It adds metabox in a admin sidebar and allows to upload image and insert its link into post content window (supports both Visual and HTML editor mode). The plugin containing a Plupload drop area just like the one found in the media uploader.

Since it uses the default WordPress functions it will compress all sizes just as the regular upload method would and it also respects any custom image sizes.

You can also choose an image from the gallery or media library, but due to restrictions the page will reload when an image is chosen from one of these locations.

###Installation

To perform a manual install, do the following:

1. Upload the `drag-drop-image` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Configure the plugin through the Settings > Drag & Drop Image options panel

###Credits

This plugin based on [«Drag & Drop Featured Image»](http://wordpress.org/extend/plugins/drag-drop-featured-image/) plugin by Jonathan Lundstrom.

###FAQ

**How to insert several images?**

At this time there no way to insert several images. I'll consider it in the next versions

**Why link to my image didn't past after upload?**

You need to select editor before uploading image.

**How do I select an image from the Media Library?**

To select a previously uploaded image from the Media Library, start by pressing the media buttons on top of the editor and go to the Media Library tab. The page will then reload (this is due to the lack of hooks for this function).

**Which image file formats extensions are currently supported?**

The current formats that are supported are JPG (JPEG), PNG and GIF

###Vesion history

v1.0 - Initial release
