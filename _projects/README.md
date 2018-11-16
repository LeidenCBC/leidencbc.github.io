# Adding a Project

## Required entries

```
layout: project
title: "Title"
shortname: Cytosplore
key: cytosplore
permalink: /projects/cytosplore/
image: cytosplore.jpg
```

title: Title to be used in the projects listing and as title on the project page
shortname: a short name of the project to be used in external listings, preferably a single word
key:  a unique key, please check other projects to avoid duplicates. The key is used for the project assets folder
permalink: preferably use /projects/KEY/
image: filename of a small teaser image to be pulled from /assets/projects/KEY/filename size the image 400x200 like the paper image

## Optional entries

Follow the example of [the cytosplore.md template](cytosplore.md) for the actual content

## Additional Files

 1. Add an md file in this folder following [the cytosplore.md template](cytosplore.md)
 2. Add a thumbnail [/assets/projects](../assets/projects/KEY] folder. Follow the guidelines for the paper thumbnail in the [papers README](../assets/papers/README.md)
 3. Optionally upload you paper video (if you have one) to vimeo and use the id in your project.md. If you have at least one video the first one will be used instead of the thumbnail on the project page
 4. Add at least the following files to `/assets/papers/KEY`
    * thumbnail figure (KEY.png) - *mandatory*  
5. Add additional files to `/assets/papers/KEY` to use the `link` entry in `documents:` and `student-projects:` otherwise use `abslink` for external links
