# Leiden Computation Biology Center Website

The Leiden Computation Biology Center website is based on the [Vis Design Lab](http://vdl.sci.utah.edu) (SCI, University of Utah) website and built with [Jekyll](http://jekyllrb.com) and [Bootstrap](http://www.getbootstrap.com).

## Setup

### Become a contributor
If you do not have a github account yet, create one.

[Send Thomas a mail](mailto:t.hoellt@lumc.nl) with your account name to be added to the contributors.

### Get the code
Clone the repository (https://github.com/LeidenCBC/leidencbc.github.io.git) to your local drive. In case you are not familiar with git an easy way is using the [Github Desktop](https://desktop.github.com/).

### Install Jekyll
If you have Ruby on your machine, just install Jekyll:

```ShellSession
$ gem install jekyll
```

Further details on installing Jekyll and its requirements:
https://jekyllrb.com/docs/installation/


## Adding Content

You can simply add/edit team members, papers and news items by adding markdown files to the corresponding folders. For the details see
 * [Adding a team member](_persons/README.md)
 * [Adding a paper](_publications/README.md)
 * [Adding a paper](_posts/README.md)

You should test your changes by running a server locally before pushing them to github:

### Running a Jekyll Server

```ShellSession
$ cd _root_folder_of_the_repository_
$ jekyll serve
```

### View the Generated Site
Open a browser and go to

```ShellSession
http://localhost:4000/
```

Refresh the page after you made any changes to any of the files

### Commit and push

If you are happy with the changes commit them to your git repository.

* First fetch any changes from the repository (Github Desktop: Fetch origin).
* Then Add a description of your changes and commit (Github Desktop: press commit to master).
* Finally push your changes to the github server (Github Desktop: push origin).
