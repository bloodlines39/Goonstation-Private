Due to the fact browse_rsc can't create subdirectories, every time you update font-awesome you'll need to change relative webfont references in fa-all.min.css eg ../webfonts/fa-regular-400.ttf => fa-regular-400.ttf (or whatever you call it in asset datum)

Second change is converting ttf to eot(ie8), and keeping ttf

Finally, removing brand related css.
