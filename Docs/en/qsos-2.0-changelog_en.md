% QSOS 2.0 Changelog
% ![Logo](Images/QSOS.png)
% Last update: 2013-02-18

# QSOS Formats
* XSD for QSOS format
* Freemind XSD for templates

# QSOS backend
* QSOS backend is now split in two repositories:
    + _Incoming_: community sandbox opened to any registered user
    + _Master_: QSOS certified evaluations and templates
* Templates and evaluations can be uploaded to the backends, this requires authentication

# XulEditor
* Remote Templates can be downloaded from the QSOS repositories and used to create a new evaluation
* Remote evaluations can be downloaded from the QSOS repositories and opened by the editor
* Evaluations can be send and saved in the remote QSOS repositories, this requires authentication
* Evaluations can be resynchronized with local or remote templates

# O3S
* 03S connects to a QSOS repository by configuration
* Better GUI internationalization, including evaluations filtering on language
* Evaluations can now be visualized in HTML and Freemind format
* Comparisons can now be visualized on a QSOS Quadrant and also be exported to OpenDocument formats (ODS, ODP and ODT)

# Documentation
* New format and mechanism adopted
    + QSOS documentation is now written in Markdown/Pandoc syntax
    + Two export format are used: PDF and Gitit wiki pages
    + Export documents are built with `make`
* QSOS Method migrated to Markdown/Pandoc
* New document: QSOS Tutorial
