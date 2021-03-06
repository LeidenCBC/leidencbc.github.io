## Creating a member profile

Please create a profile using the following template.
Don't remove rows if you don't have the information right now, just leave the data empty.
E.g., if you don't know what your interests are yet, leave the field blank but don't delete "interests".

the file should be save to
```
/_persons/_unique_key_.md
```

```
---
layout: default
first_name:
last_name:
key:
permalink:
role:
email:
image:
organization:
position:
website:
interests:
graduated:
---
```

For a description of the entries see bottom of the page.
## Creating a collaborator profile

Use "role: collaborator" for collaborators on papers. Note that this isn't strictly necessary, you can just type the person's full name in the author list, but it might be useful if you're collaborating with a person a lot.

## Complete, documented profile
```
---
# layout: use default only for now
# person generates a local page for you (not properly implemeted, yet)
layout: deafult | person
first_name: _first_name_
last_name: _last_name_
# find a unique key for you, i.e. your last name
key: _unique_key_
# the permalink points to your page if used, and should be /team/_unique_key_/
permalink: /team/_unique_key_/
# Pick one of the following roles
role: faculty | phdstudent| postdoc | msstudent | collaborator | advisor
email: your@email.address
# the image points to your headshot, and should be /assets/images/team/_unique_key_.jpg|.png
# make sure to add the image to the folder
image: /assets/images/team/_unique_key_.jpg
# add the full name of the organization, no abbreviations
organization: Leiden University Medical Center
position: Assistant Professor
# use either a local link (i.e. your permalink /team/_unique_key_/), or any URL
website: /team/_unique_key_/ | https://www,yourwebsite.com
interests: List your research interests here
#  leave empty if you're active. Add something like "M.S.'16" or "B.S.'17" if you got a degree while at LCBC. Add "N" if you left LCBC before you got a degree.
graduated:

# stuff below can be ignored if you don't use the group website for your private website

# link to google scholar
gs:
# link to github
gh:
# link to github
twitter: "@twitterhandle"
# link to a cv pdf
cv:
address: |
    Leiden University Medical Center <br>
    Computational Biology Center <br>
    _street_ <br>
    _zip_ Leiden

# free format content goes below this line, use markdown to format
---
```
