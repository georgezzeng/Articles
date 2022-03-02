---
published: false
---

# Articles
Contains all articles published on the various CHTC influenced websites.

## Previewing a Article
Previews are generated from the development branch. Add an article there and look for it in the list on https://chtc.github.io/article-preview/ to see the preview. 

## Creating a new Article
To create a new article add a new file to the root of this repo with the following format:

```markdown
YEAR-MONTH-DAY-title.md
```

Then include the following frontmatter

```yaml
---
title: 
author: 
publish_on:
    - <htcondor, path, osg, chtc>
canonical_url: 
image:
  path: https://raw.githubusercontent.com/CHTC/Articles/main/images/...
  alt: 
description: <This is used as a link description when this article is linked>
excerpt: <Same as description but used for the cards>
card_src: https://raw.githubusercontent.com/CHTC/Articles/main/images/...
card_alt: 
banner_src: <optional> https://raw.githubusercontent.com/CHTC/Articles/main/images/
banner_alt: <optional>
---
```

## Things to remember when working in this folder

- `date` is omitted on purpose, Jekyll populates this field from the filename.
    - Discrepancy in front matter and filename dates can cause unexpected results

- All images must be absolute
    - As these images will be served from a variety of folders and depths you must use an absolute url 
    - Absolute URL to use: `https://raw.githubusercontent.com/CHTC/Articles/main/images/`
    
