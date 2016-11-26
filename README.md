# bandcampdl
Downloads music albums and tracks from Bandcamp

Run the `bandcampdl` script with each url as an argument to download the cooresponding albums from Bandcamp.
It **will** warn you if you attempt to download some sort of album collection.

The `bandcampdl-artist` script is a wrapper for the `bandcampdl` script. **For it to work, they _must_ be in the same directory.**
It takes one argument (the bandcamp home page of an artist) and downloads _all_ of their albums.

`bandcampdl` depends on:

 - GNU wget
 - grep
 - bash
