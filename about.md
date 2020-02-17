---
layout: page
title: About
permalink: /about/
---

This is an experimental site for publishing fictions and think-pieces. Don't
mail the owner at [{{site.email | escape}}](mailto:{{site.email | escape}}). He
doesn't like people, unless they have some chocolate.

## How to Contribute

If you want to add your writing to this site, **either mail [Enan
Ajmain](mailto:3nan.ajmain@gmail.com)** or follow the instructions below.

1. Create a Github account.
2. Fork this repository.
3. Convert your document to markdown.
   - For `DOCX` files, you can use `pandoc` to convert to `MARKDOWN` format.
   ```
   pandoc -f docx -t markdown filename.docx
   ```
   - For other filetypes, search on the internet. It should be easy to find.
4. Add your piece to the directory `_posts`. Check the posts already in that
   directory to get an idea of the format. Double check to see if your name
   and email are in the front matter of the post; those are necessary for the
   website to categorize the writings.
5. Commit the changes and push to remote.
6. Create a merge request.
