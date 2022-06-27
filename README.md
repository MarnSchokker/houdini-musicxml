# houdini-musicxml

Houdini package for MusicXML import, export and processing.

At this moment the project supports part-wise documents and follows the MusicXML 4.0 specification. 

After import, polylines are created for each musical voice for each instrument. 

Included are hip demoscenes and musicxml sample files.

# Introduction video

[![houdini-musicxml introduction video](https://img.youtube.com/vi/6vhpkzlGj78/0.jpg)](https://www.youtube.com/watch?v=6vhpkzlGj78)

# Installation

You can install houdini-musicxml using the packages system. 

1. Download the repository using the green Clone or Download Button and unzip contents into a folder that Houdini scans for packages. For example: Program Files/Side Effects Software/sidefx_packages or $HOUDINI_USER_PREF_DIR/packages

2. Move the houdini-musicxml.json up one level in explorer, so it's next to the extracted folder.

# To do

- prim attribute of generatered polylines for instrument name
- Convert header detail string attributes to dictionary attributes.
- A broader toolset for analysis and editing, for example by adding VEX snippets / presets.
- Automated regression testing

