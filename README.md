# 简历生成器（基于 Ruby）

通过填充一个 YAML 文档并把它编译为 HTML 和 CSS 代码，你可以在几秒钟内创建你自己的简历。

![alt text](http://ww2.sinaimg.cn/large/73a07e94jw1f3gzgfcwilj21kw0tojyt.jpg "实际生成的个人简历效果图")

## 如何开始制作？

- 把这个代码库 clone 到你的机器上。
- 使用 `bundle install` 命令，安装 Gemfile 中列举的 gems。
- 把 `data/info.yaml.example` 改名为 `data/info.yaml`，对 `data/_variables.scss` 文件也进行这样的改名操作。
- 运行 `ruby app.rb`
- 现在，你的个人简历文件已经在 `export` 文件夹中了。

## 请随意进行自定制

- 你可以在 `data/_variables.scss` 中修改颜色和字体。
- 你可以通过在 `data/info.yaml` 文件的 `links` 数组中指定的方式，导入其它的 Google 字体。
- 你可以创建一个名为 `assets` 的文件夹，其中的内容会被复制到 `export` 文件夹下。

简历模板由 [Franklin Schamhart](https://dribbble.com/shots/1887983-Resume) 设计

## 版权信息

此代码的版权人是 Merijn Hoogeveen，pimgeek 在 Merijin 的代码基础上做了一些自定制。

此项目使用 MIT license 进行授权。
