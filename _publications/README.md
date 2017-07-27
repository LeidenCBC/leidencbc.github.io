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
2016_eurovis_cytosplore.pdf
```
If there's multiple files of the same type, the "secondary" type is specified with an underscore:
```
2016_eurovis_cytosplore_supplement.pdf
```

 1. Add an md file in this folder following [this template](2016_eurovis_cytosplore.md)
 2. Add a thumbnail AND a larger teaser figure to the [/assets/papers](../assets/papers] folder. Read more about this in the [papers README](../assets/papers/README.md)
 3. Upload you paper video (if you have one) to vimeo and use the id in your paper.md
 4. Add the following files to `/assets/papers/YYYY_CONFSHORTNAME_PAPERSHORTNAME`
    * Paper PDF (KEY.pdf) - *mandatory*
    * thumbnail figure (KEY.png) - *mandatory*
    * bibtex file (KEY.bib) - *to be removed, but mandatory for now*    
    * Supplementary Material PDF (KEY_supplement.pdf)
