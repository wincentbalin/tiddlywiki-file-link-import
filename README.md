# Import links to files into TiddlyWiki

This is a helper utility to import links to files, _instead of_ the files themselves, into TiddlyWiki as tiddlers.

Every file is embedded within a HTML tag, corresponding to its main content type:

Main content type|HTML tag
-----------------|--------
`image/`         |`img`
`audio/`         |`audio`
`video/`         |`video`
Everything else  |`a`

As you can see, any unknown content type is embedded as link.


