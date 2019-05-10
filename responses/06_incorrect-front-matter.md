## Checking your front matter

It looks like there may be some errors in your front matter. Take a look at your front matter and make sure the following is true:

- [{% if dashes %}x{% else %} {% endif %}] You used dashes on the first and final line
- [{% if title %}x{% else %} {% endif %}] You added a page title surrounded in quotes
- [{% if date %}x{% else %} {% endif %}] You added a date using the correct format

The YAML front matter should be at the top of your blog post file and should look something like this:

```yaml
---
title: "Your blog post title"
date: YYYY-MM-DD
---
```

### :keyboard: Activity: Edit your blog post

1. Click the "Files Changed" tab in this pull request.
1. Scroll past the config file, and find the file that you created.
1. Click on the pencil icon on the right side of the screen.
1. Make adjustments based on the above errors.
1. Scroll to the bottom, and commit your changes.

If you would like assistance troubleshooting the issue you are encountering, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past.

<hr>
<h3 align="center">Watch below for my response.</h3>
