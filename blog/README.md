# blog

Abakhi's blog


## Setup

* Install [Jekyll](https://jekyllrb.com/)
* Run site: ```$ jekyll serve```


## Updating website blog

To publish a new post or make changes to the blog, publish the html files into the subfolder under the website repo. Assuming you have clone both repositories into the same folder, type:

```$ jekyll build -d PATH-TO-WEBSITE/blog```

For example, ```$ jekyll build -d ../website/blog```

This will put the html Jekyll processed files in blog folder under the website repo. And then push to publish!
