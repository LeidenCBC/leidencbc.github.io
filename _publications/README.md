# Adding a Paper

## Keys and File Names

Each paper must have a key following this pattern:

```
YYYY_CONFSHORTNAME_PAPERSHORTNAME
```

All files should be named uniformly based on the following pattern: 

```
YYYY_CONFSHORTNAME_PAPERSHORTNAME.EXTENSION
```
E.g.:
```
2016_eurovis_pathfinder.pdf
```
If there's multiple files of the same type, the "secondary" type is specified with an underscore:
```
2016_eurovis_pathfinder_supplement.pdf
```


 1. Add a md file in this folder following [this template](2016_eurovis_pathfinder.md)
 2. Add a thumbnail AND a larger teaser figure to the [assets/images/papers](../assets/images/papers] folder. Read more about this in the [image README](../assets/images/papers/README.md)
 3. Upload you paper video (if you have one) and your preview video to youtube and create an entry in the [videos folder](../_videos) folder.
 4. Upload the following files to `/usr/sci/www/vdl/papers`
    * Paper PDF (KEY.pdf) - *mandatory*
    * thumbnail figure (KEY.png) - *mandatory*
    * bibtex file (KEY.bib) - *mandatory*    
    * Supplementary Material PDF (KEY_supplement.pdf)
    * full video (KEY.mp4)
    * preview video (KEY_preview.mp4)
    
Here is a sync script that you can run to sync a local folder with the sci folder. 
```bash
rsync * alex@shell.sci.utah.edu:/usr/sci/www/vdl/papers --protocol=29 -r
```


 