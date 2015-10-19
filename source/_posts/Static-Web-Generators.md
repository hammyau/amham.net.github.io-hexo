title: Hexo Static Web Generator
date: 2015-10-18 15:59:26
tags:
---

The page https://www.staticgen.com/ list a number of static web site generators.
This is from Hexo which is highly starred.

It was plain sailing to get this far.

Now... how easy is it to configure and deploy?

Where did my layout go?

Not so easy to change the layout...
Just requires some reading...?

Different templates are supported.
Default seems to be {% link swig http://paularmstrong.github.io/swig/ %}
But can also have Jade or EJS.

There are also some to choose from via {% link themes https://hexo.io/themes/ %}

There is a great source of Hexo info at {% link jr0cket http://jr0cket.co.uk/hexo/index.html %}
Many thanks John.

The biggest issue I had was in getting it to deploy on Github.

The key is in setting the values for url and root in the _config.yml file.

When they were not set correctly the css wasn't found and we had plain html with no prettiness.

So I have the basis now and will change the layout in the future.
