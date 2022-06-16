# 小组主页使用说明和配置日志

## 使用说明

### 安装 Ruby, RubyGems, Jekyll 和 Bundler

参考文档 [Jekyll Docs](https://jekyllrb.com/docs/installation/)

在 [Downloads (rubyinstaller.org)](https://rubyinstaller.org/downloads/) 安装 `Ruby+Devkit`. 运行安装文件将其安装到 `C:/`. 

运行

``` bash
gem install jekyll bundler
```
Mac 上环境配置需要注意使用 Homebrew 下载新的 ruby, 具体方法见[这篇文章](https://zhuanlan.zhihu.com/p/350462079).

### 初次部署

使用如下命令预览

```bash
bundle exec jekyll server
```

报错

```bash
cannot load such file -- webrick
```

运行 `bundle add webrick` 安装. 再次尝试预览, 成功!

### 创建文章

在 `_posts` 目录中按照已有文件的格式创建新文件即可. 在使用

```bash
bundle exec jekyll server
```

预览的过程中, 浏览器中内容可即时刷新. 此时已生成对应文件. 因此直接 add - commit - push 即可完成部署.

## 配置日志

- 20220616, 申请账户 [QuantumObserverIASTU](https://github.com/QuantumObserverIASTU), 建立仓库 [QuantumObserverIASTU.github.io](https://github.com/QuantumObserverIASTU/QuantumObserverIASTU.github.io), 将 [PhD.Physics.Dog](https://github.com/Florestan-Eusebius) 加入仓库的合作者.
- 20220616, 使用 [Huxpro](https://github.com/Huxpro/huxpro.github.io) 模板搭建.
