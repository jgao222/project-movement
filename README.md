Team website for Project Movement as part of CSE 481 D at University of Washington

Contributors please push to `dev` branch and ensure everything looks okay locally
before opening a pull request into `main`, since every time `main` gets updated
the deployment changes. Hopefully we can not deploy any broken/incomplete versions
by doing it in this way.

Note on adding resources: use relative paths, not absolute or root-relative paths. Since we are
not building the site with any static generation tools, those won't end up pointing
to the right place.