# Oliver Fried's blog


A small Jekyll blog inspired by https://www.moderndescartes.com/.
Hosted on GitHub Pages at https://oliverfried.org.


## Publish an essay


Create a file named `_posts/YYYY-MM-DD-your-title.md` (Add file → Create new file).
Start it with:


```markdown
---
title: Your title
tags: [software, personal]
---


Write your essay in Markdown here.
```


Use today's date or an earlier date. Commit to main. GitHub Pages publishes automatically.
Posts appear on the home page with their title and writing date, and in the RSS feed.
The file in _drafts is a template and stays unpublished.


## Edit the home page


Edit index.md. Change the site name and description in _config.yml, and the design in style.css.


## Hosting


Settings → Pages: main branch, root folder. Custom domain: oliverfried.org.
Namecheap apex A records: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153.
www CNAME: oliver-fried.github.io. Preserve mail-related DNS records.
Enable Enforce HTTPS when the certificate is ready.

