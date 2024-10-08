# About us

**Brain-Computer Interface and Hardware Acceleration Laboratory**
of Northeastern University

this is an Academic Blog

---

### 关于如何使用与更新

#### 对刚接触GitHub的同学,请阅读我们编写的[东秦自救手册](https://manual.caiyi1.me/)中关于md与git的相关内容

#### 首先,如果遇到很高级的定制问题,请阅读官方文档[Minimal MistakesA Jekyll theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/)

### 启动本地预览
要在本地运行并预览 Jekyll 网站，你需要按照以下步骤操作：

1. 安装 Ruby 和 RubyGems
Jekyll 是用 Ruby 编写的，所以首先需要安装 Ruby 和 RubyGems（Ruby 的包管理工具）。

macOS: 使用 brew install ruby
Windows: 你可以通过 RubyInstaller 安装 Ruby。
Linux: 使用系统的包管理器（如 apt, dnf）安装 Ruby，比如在 Ubuntu 上执行 sudo apt install ruby-full
终端进入在此文件夹目录下,或者直接在vcode的集成终端中输入:
```
gem install jekyll bundler
bundle install
bundle exec jekyll serve
```
或者点击笔者写好的`start.bash`文件

### 修改字体大小(主页除外)
强烈建议使用`内联式`写法!!!!!!由于主题的精细结构,直接指定style会直接动全部文字!
![mdimage](mdimages/fontsize.png)
调节不同**h**,不同**p**的参数可以直接将网页中的字体比例发生变化(需要一定的html知识

**注意,还有一个更加细微的微调旋钮可以精细调节原始比例,但不建议**
![0](mdimages/fontori.png)

### 修改主页字体大小
强烈建议使用`内联式`写法!!!!!!由于主题的精细结构,直接指定style会直接动全部文字!
需要一定的前端知识,具体是html的语法规范
修改`<div>`指定的`font-size`比例
![0](mdimages/indexfont.png)

### 常用功能:修改左侧栏信息:
![mdimages](mdimages/左侧栏.png)
在`_config`中找到以上内容,即可定制bio,图片等相关信息

### 常用功能:修改左上角title
![mdimages](mdimages/左上边栏.png)
在`_config`中找到以上内容,即可定制logo,title等相关信息

### 常用功能:修改navigate
![0](mdimages/navigation.png)

打开navigation.yml文件,按照想展示的先后顺序添加新的标签栏,并给每个标签栏分配唯一的url

![0](mdimages/转跳.png)

在网页中点击navigation之后,这个模板会去这里找相关的md文件或者html文件

![0](mdimages/_pages.png)

在相应的md或者html文件中,我们一般需要添加

```
---
title: "这个网页显示在最上面的标题"
permalink: /在navigation.yml中指定的url/
---
```
当然,这些东西大家随便找一个之前写过的文档模仿一下就可以了,相关页面可以使用html或者md编写,都能正常解析
这里笔者放心不下补充一点:layout的值`_pages`文件夹里面的文件一般不添加,**但是index.md或者index.html**一定要使用`layout:home`!

#### 修改主页index
直接修改根目录中那个index文件即可

![0](mdimages/index.png)

#### 提交post
将md文件按照YY-MM-DD-Title.md命名即可,并放入

![0](mdimages/post.png)
中

 using the theme:[Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/)

[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/LICENSE)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.7-blue.svg)](https://jekyllrb.com/)


## License

The MIT License (MIT)

Copyright (c) 2013-2024 Michael Rose and contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Minimal Mistakes incorporates icons from [The Noun Project](https://thenounproject.com/) 
creators Garrett Knoll, Arthur Shlain, and tracy tam.
Icons are distributed under Creative Commons Attribution 3.0 United States (CC BY 3.0 US).

Minimal Mistakes incorporates [Font Awesome](http://fontawesome.io/),
Copyright (c) 2017 Dave Gandy.
Font Awesome is distributed under the terms of the [SIL OFL 1.1](http://scripts.sil.org/OFL) 
and [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates photographs from [Unsplash](https://unsplash.com).

Minimal Mistakes incorporates [Susy](http://susy.oddbird.net/),
Copyright (c) 2017, Miriam Eric Suzanne.
Susy is distributed under the terms of the [BSD 3-clause "New" or "Revised" License](https://opensource.org/licenses/BSD-3-Clause).

Minimal Mistakes incorporates [Breakpoint](http://breakpoint-sass.com/).
Breakpoint is distributed under the terms of the [MIT/GPL Licenses](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [FitVids.js](https://github.com/davatron5000/FitVids.js/),
Copyright (c) 2013 Dave Rubert and Chris Coyier.
FitVids is distributed under the terms of the [WTFPL License](http://www.wtfpl.net/).

Minimal Mistakes incorporates [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/),
Copyright (c) 2014-2016 Dmitry Semenov, http://dimsemenov.com.
Magnific Popup is distributed under the terms of the MIT License.

Minimal Mistakes incorporates [Smooth Scroll](http://github.com/cferdinandi/smooth-scroll),
Copyright (c) 2019 Chris Ferdinandi.
Smooth Scroll is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [Gumshoejs](http://github.com/cferdinandi/gumshoe),
Copyright (c) 2019 Chris Ferdinandi.
Gumshoejs is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [jQuery throttle / debounce](http://benalman.com/projects/jquery-throttle-debounce-plugin/),
Copyright (c) 2010 "Cowboy" Ben Alman.
jQuery throttle / debounce is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [GreedyNav.js](https://github.com/lukejacksonn/GreedyNav),
Copyright (c) 2015 Luke Jackson.
GreedyNav.js is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [Jekyll Group-By-Array](https://github.com/mushishi78/jekyll-group-by-array),
Copyright (c) 2015 Max White <mushishi78@gmail.com>.
Jekyll Group-By-Array is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [@allejo's Pure Liquid Jekyll Table of Contents](https://allejo.io/blog/a-jekyll-toc-in-liquid-only/),
Copyright (c) 2017 Vladimir Jimenez.
Pure Liquid Jekyll Table of Contents is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [Lunr](http://lunrjs.com),
Copyright (c) 2018 Oliver Nightingale.
Lunr is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [clipboard.js](https://clipboardjs.com/),
Copyright (c) 2021 Zeno Rocha.
Clipboard.js is distributed under the terms of the [MIT License](https://opensource.org/licenses/MIT).
