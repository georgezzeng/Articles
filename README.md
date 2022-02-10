---
published: false
---

# Articles
Contains all articles published on the various CHTC influenced websites.

## Creating a new Article
To create a new article add a new file to the root of this repo with the following format:

```markdown
YEAR-MONTH-DAY-title.md
```

Then included the following frontmatter

```yaml
---
title: 
websites:
    - <htcondor, path, osg, chtc>
canonical: <htcondor, path, osg, chtc>
banner_src: 
card_src: 
card_alt: 
excerpt: |
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce consectetur 
    enim lacus, eget feugiat turpis porta sit amet. Mauris cursus lectus vitae 
    luctus accumsan. Nullam sit amet condimentum tortor, sed feugiat augue. Quisque 
    lobortis neque non aliquam faucibus. Nam ultrices nunc ex, sed pulvinar orci 
    bibendum in.
---
```

**Notice:**

`date` is omitted on purpose, as jekyll populates this field from the filename.