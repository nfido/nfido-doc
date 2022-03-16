# 首页

本文档基于mdbook 构建而成，你可以安装mdbook，然后本地开发，或者运行文档站点

先安装mdbook, 没有安装可以用下列 命令安装。

目前作者在Mac 下面进行开发，所以下面的命令，在mac上工作ok，linux理论上都可以正常工作。

```bash
cargo install mdbook
```

如果你连cargo都没有，那你需要装一下rust 

mdbook装好之后，可以本地运行

```bash
cd ./nfido-doc
mdbook serve
```

然后你可以打开浏览器，访问http://localhost:3000

就可以看到本文档了.