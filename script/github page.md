# github page

problem 1:

总是去加载当前目录下的`index.md`。

通过`_layouts`目录下的布局，决定各个页面。

`_posts`目录是你的文章的目录。

`History.markdown`相当于是一个页面。

`_config.yml`为配置文件。

如果要在页面添加目录需要在相应的`.md`文件头部加入：

```markdown
* TOC
{:toc}
```

参考这里http://www.seanbuscay.com/blog/jekyll-toc-markdown/

