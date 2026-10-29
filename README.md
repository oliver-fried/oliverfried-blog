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

Keep each post's filename slug in sync with its title. When changing a title,
rename the file to match and add its old URL to `redirect_from` in the front matter.
Keep earlier redirects when adding a new one so shared links still work.




## Edit the home page




Edit index.md. Change the site name and description in _config.yml, and the design in style.css.
