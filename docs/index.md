## Purpose

Often one or more github repos and google docs repositories are used in a single github project.   For example:  Front end and back end.  In addition multiple public or private share for binary documents are also used.    This project will serves as a wrapper for both of those conepts as well as being a single repository for documentation.

This project uses mkdocs to provide an simple platform to generate html pages from markdown.   It can be hosted anywhere, includes special provisions for ghpages or can be run locally with ```mkdocs serve```

## Topcoder Theme
This repository uses a third party theme called [cinder](https://github.com/chrissimpkins/cinder).   However this theme has been forked and added the topcoder logo <img src="https://storage.googleapis.com/instapage-user-media/97c829ee/1997047-0-high-topcoder-horizo.png"  height="22px"/>.   It would be easy enough to include this forked code directly in the tcProjWrapper repo directly, except this project relies heavily on  submodule for src so we wanted to include the theme as a submodule too.  In addition the submodule could be forked or branched specifly to include a customers logo.

## Topcoder Docs
Since this project also contains content,  We can include standard docs like bug bash instructions.
