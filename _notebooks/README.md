# Auto-convert Jupyter Notebooks To Posts

[`fastpages`](https://github.com/fastai/fastpages) will automatically convert [Jupyter](https://jupyter.org/) Notebooks saved into this directory as blog posts!

You must save your notebook with the naming convention `YYYY-MM-DD-*.ipynb`.  Examples of valid filenames are:

```shell
2020-01-28-My-First-Post.ipynb
2012-09-12-how-to-write-a-blog.ipynb
```

If you fail to name your file correctly, `fastpages` will automatically attempt to fix the problem by prepending the last modified date of your notebook. However, it is recommended that you name your files properly yourself for more transparency.

See [Writing Blog Posts With Jupyter](https://github.com/fastai/fastpages#writing-blog-posts-with-jupyter) for more details.

## Notebook Blog
1. put notebook with output in _notebook
2. push the changes to master and let GH actions create the blog


```py
# "Matplotlib Guide - p2"
> "Plotting data with matplotlib. Different types of Charts"

- author: Bhargav Lad
- toc: true 
- badges: true
- comments: true
- image: images/mplib2.png
- categories: [ jupyter,matplotlib]
```
