# The Alumni Blog

This directory contains blog entires, written in the Markdown format. 
The entires are sorted by filename and automatically placed under the [/blog/](../index.html) subdirectory of the website. 

Each file requires some front matter with the following attributes:

* `layout:` has to be set to `blogpost` for entry to show up as a blog post
* `title`: the title of the post
* `date`: the date of the post in the format like `September 16th, 2014`
* `author`: the name of the author of the post
* `permalink`: the link to the blog post. Should end in a slash and be something like `/blog/heart-jet-lag/`
* `titleImage`: optional name of an image to use as the title image of the post. Should be stored in the `/media/` folder
* `preview`: text providing a preview of the article, used to fill tiles on the overview page

See the existing entires for examples. 