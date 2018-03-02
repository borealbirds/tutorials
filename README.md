# Boreal Avian Modelling Project Tutorials

Here is an example post (a markdown file):

```
---
title: "North America Land Cover Maps"
category: gis
tags: [land cover, North America, MODIS]
---

Other MODIS landcover products exist at the North America extent (resolution 250m, 19 landcover classes):


<center>
<img src="{{ site.baseurl }}/images/{{ page.category }}/map2.png" class="img-responsive" alt="NALCMS" width="80%">
</center>
```

The file would be named `2000-01-01-file.md` where the date
must be present because this helps jekyll to sort the files (i.e. if you want
to list the files in a defined order, use increment the day, or the month).
But date is not used/printed, because this is not a blog.

The file would into a folder `/<category>/_posts/2000-01-01-file.md`.
The folder name (`category`) must match the page category (here
it is called `category: gis`, so the file is to be found at
`/gis/_posts/2000-01-01-file.md`.

The list of categories is defined in the `_config.yml` file.

The piece between the `---` triple dashes is called the YAML header,
it defines metadata for the page.
The `title` will be printed, so the file does not have to have a title
(e.g. a line like `# Title`). You can also have a `subtitle` field.

The `tags` field is also useful, because we can group pages based on tags.

Images need to be treated somewhat specially, otherwise
the image will be displayed according its original dimensions,
and will not be responsive at all.
Therefore, we have to wrap it the way it is shown above.

The page source is defined as `{{ site.baseurl }}/images/{{ page.category }}/map2.png`.
The `{{ site.baseurl }}` is defined in `_config.yml`,
`{{ page.category }}` is the category from the file header.
So the image would be filed in the `/images/<category>/` folder.
There can be other subfolders (post specific ones etc.),
but those have to be nested in the category.
