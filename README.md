# blogs

## How to write a post.
You can write a post in markdown. 
### Post YAML
```yaml
---
layout: post # Specify the template file to be used. The template file name in the "_layout" directory determines the variable name
title: title # The title of the article
date: date # Override the date in the article name
category: blog # The category of the article
desc: description
published: true # default true After setting "false", the article will not be displayed
---
```
### Post Setting
* Location: Place your article in the `_posts` directory (make sure it's `_posts`, not `posts`).
* File naming convention: Use the format `YYYY-MM-DD-title.md` for your file name, such as `2023-10-01-my-first-post.md`.
* Then push the new blog.
