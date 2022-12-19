# Import links to files into TiddlyWiki

This is a helper utility to import links to files, _instead of_ the files themselves, into TiddlyWiki as tiddlers.

Every file is embedded within a HTML tag, corresponding to its main content type:

Main content type|HTML tag
-----------------|--------
`image/`         |`img`
`audio/`         |`audio`
`video/`         |`video`
Everything else  |`a`

As you can see, any unknown content type is embedded as a link.

# How to

1. Drag the files (**without directories!**) onto the page of the tool and drop them when the background turns light green, as you probably already saw in TiddlyWiki. If everything worked as expected, the list of dropped files will appear.
2. Drag the list of dropped files to TiddlyWiki and import the resulting tiddlers as usual.
