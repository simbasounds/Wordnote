# Wordnote
## A WordPress-based notebook

This document will begin by listing a few primary features of Evernote and similar apps, and how those features can be achieved using a WordPress-based system. Shameless standing on giant shoulders has been deemed acceptible in the spirit of the platform, which is to say any third-party plugin, theme, or embedded service is fair game.

This will be a constantly-updated project, as yet starting out and incomplete as at this time. For now it's a few descriptions and instructions, but will include code snippets, php templates, themes, custom plugins, and installers if / when they materialise.

Assuming WordPress is being considered, the massive extensibility of the platform can be utilised to take an instance in any direction well beyond what traditional notebook services and systems have to offer. Some allusion may be made to the possibilities here, while staying within the scope.

WordPress is well-tooled for the purpose of taking, editing, classifying, sorting, searching and displaying notes. Posts already have many of the features of notes, such as categories and tags.

## Importing
For existing Evernote users, getting your notes into a WordPress database as posts is possible using a number of methods.
### Note Update Sync Methods
When you create or update a note, a WordPress post is created or updated. This can be used to migrate existing notes by applying a small change to them, such as adding a tag, which triggers an update. There are [manual methods](https://discussion.evernote.com/topic/62196-export-to-wordpress/?do=findComment&comment=343863), WordPress plugins such as [EverPress](https://wordpress.org/plugins/everpress/) and [Sentinote](https://wordpress.org/plugins/sentinote/), general services such as [IFTT (link to module)](https://ifttt.com/connect/evernote/wordpress) and [Zapier](https://zapier.com/zapbook/evernote/wordpress/), and more dedicated services such as [EaTags](https://eatags.com/).

## Note Migration Services
Incomplete

### Export / Import method
The method that worked for me was exporting all (about 900 in my case) notes from Evernote as HTML files, then importing them again using HTMLImport2 WordPress plugin, which required some specific settings to get this right. I'll cover those shortly.

## Note Management
### Creation
To work with "notes" in WordPress, Simply create, edit and view WordPress posts. Some features, such as front end editing may be added using plugins, such as the [Front-end Editor for WordPress](https://en-za.wordpress.org/plugins/wp-front-end-editor/).

### The Web Clipper - PressThis?
PressThis works as a basic content clipper, although something with the functionality of the great Evernote Web Clipper is currently being sought.

## Classification
### WordPress Categories as Evernote Tags
WordPress categories - being hierarchical - are similar enough to Evernote's hierarchical tags to warrant their usage as a replacement. Evernote tags are sorted-only, not hierarchically functional, so there is already some advantage in WordPress's system.

### Custom Taxonomy for Notebooks
Notebooks can be defined using a subset of categories on the existing system, or a custom hierarchical taxonomy can be used for more separation. However, seeing as anything is possible, a special note type may be desired with a custom CMS. Any number of these may be possible when utilising Custom Post Types.

