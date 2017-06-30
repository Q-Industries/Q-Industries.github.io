the hugo bootstrap-theme uses index.* files, while the frais-theme uses _index* files

copy these files into the /content folder if you like to activate the hugo-bootstrap theme

Note: the bootstrap theme has a  complex rendering logic

/ is reendered using index.html
but
/en (the root of the default language) is rendered with /default/single.html
This is very different from the frais-theme where /, /en (default), /fr, etc. are all rendered by  index.html
