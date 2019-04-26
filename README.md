# Autonomous Vision Blog

This is the blog of the Autonomous Vision Group at MPI-IS Tübingen and University of Tübingen.
You can visit our blog at <https://autonomousvision.github.io>.
Also check out our [website](https://avg.is.tuebingen.mpg.de/) to learn more about our research.

## Instructions for Authors

To write a new blog entry, first register yourself as an author in [authors.yml](https://github.com/autonomousvision/autonomousvision.github.io/blob/master/_data/authors.yml).
Here, you can also add your email address and links to your social media accounts etc.

You can then create a new blog post by adding a markdown or html file in the [_posts](https://github.com/autonomousvision/autonomousvision.github.io/tree/master/_posts) folder.
Please use the format `YYYY-MM-DD-YOUR_TITLE.{md,html}` for naming the file. You can then create a yaml header where you specify the author, the category of the post, tags, etc. For more information, take a look at existing posts and the [Minimal Mistakes documentation](https://mmistakes.github.io/minimal-mistakes/docs/posts/).

If you want to include images or other assets, create a subfolder in the [assets/posts](https://github.com/autonomousvision/autonomousvision.github.io/tree/master/assets/posts) folder with the same name and the filename of your blog post (without extension).
You can simply reference your assets in your post using `{{ site.url }}/assets/posts/YYYY-MM-DD-YOUR_TITLE/` followed by the filename of the corresponding asset.
Make sure that you don't forget to include the `{{ site.url }}`! While the post while be rendered correctly without the `{{ site.url }}`, the images in the newsfeed will break if you don't include it.

## References
You can find more information here:

* [Jekyll documentation](https://jekyllrb.com/)
* [Minimal Mistakes documentation](https://mmistakes.github.io/minimal-mistakes/)
