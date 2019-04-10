---
layout: post
title: Web Online Code Editor
date: 2019-04-03 19:06:18
tags:
  - Web
  - Env
---

Web Online Code Editor 顾名思义，是依靠浏览器以及后台编译服务器的一个在线代码编辑器。它不依赖于操作系统，无需搭建繁琐的本地环境，无需了解构建流程即可快速实现前端代码逻辑。业内更多的使用它进行 Demo 展示、Live Coding、Interview 等场景。

这篇文章旨在对主流的 Online Code Editor 产品进行一次简单直面的对比和测评；帮助大家更好地选择选择 Online Code Editor 产品。

<!-- more -->

## Contrast

那么 IDE 和 Editor 是何关系？关于这个问题，知乎上有个答案我很认可：『IDE 和 Editor 是包含和被包含的关系，IDE 内置了 Editor』

便捷性：IDE < Editor < Web Online Code Editor
能力覆盖：IDE > Editor > Web Online Code Editor

### IDE

IDE 帮我们处理了很多事情：创建文档索引缓存、Code Snippet、Autocomplete、Debug、依赖管理、项目管理、版本控制、代码跳转、Dubug、代码高亮、调试、运行。
侧重：开发

### Editor

Editor 在文档编辑的基础上，引用插件的机制在一定程度上降低了 Code Edit 的使用成本。
侧重：编辑代码

### Online Code Editor

Online Code Editor 更多像是一种 Draft；快速实现、验证想法。它通过浏览器或者与后台编译服务器，默认定制了一套开发环境，使用前端开发成本大大降低。
侧重：草稿

## Feature

|       Production        | Thimble[↗](#Thimble) | Dabblet[↗](#Dabblet) | CodeSandbox[↗](#Codesandbox) |  Playcode[↗](#Playcode)   | Codepen[↗](#Codepen) | Stackblitz[↗](#Stackblitz) |        JSBin[↗](#JSBin)        | Babeljs[↗](#Babeljs) | TypeScript[↗](#TypeScript) | CodeInterview[↗](#CodeInterview) |    Glitch[↗](#Glitch)     |
| :---------------------: | :------------------: | :------------------: | :--------------------------: | :-----------------------: | :------------------: | :------------------------: | :----------------------------: | :------------------: | :------------------------: | :------------------------------: | :-----------------------: |
|      Highlighting       |          ✔           |          ✘           |              ✔               |             ✔             |          ✔           |             ✔              |               ✘                |          ✔           |             ✔              |                ✔                 |             ✔             |
| Linting & ErrorChecking |          ✘           |          ✘           |              ✔               |             ✔             |          ✘           |             ✔              |               ✔                |          ✔           |             ✔              |                ✘                 |             ✔             |
|       Formatting        |          ✘           |          ✘           |              ✔               |             ✔             |          ✘           |             ✔              |               ✘                |          ✘           |             ✘              |                ✘                 |             ✘             |
|     AutoCompletion      |          ✔           |          ✘           |              ✔               |             ✔             |          ✘           |             ✔              |               ✘                |          ✘           |             ✘              |                ✘                 |             ✘             |
|        Debugging        |          ✘           |          ✘           |              ✘               |             ✘             |          ✘           |             ✘              |               ✘                |          ✘           |             ✘              |                ✘                 |             ✘             |
|      **Compiler**       |
|       ES Compiler       |          ✘           |          ✘           |              ✔               |             ✔             |          ✔           |             ✔              |               ✔                |          ✔           |             ✘              |                ✔                 |             ✔             |
|       TS Compiler       |          ✘           |          ✘           |              ✔               |             ✔             |          ✘           |             ✔              |               ✔                |          ✘           |             ✔              |                ✔                 |             ✔             |
|         **CSS**         |
|      Preprocessors      |         CSS          |         CSS          |  CSS,Stylus Sass,SCSS,Less   | CSS,Stylus Sass,SCSS,Less |         CSS          |     CSS Sass,SCSS,Less     | CSS,Myth,Stylus Sass,SCSS,Less |          -           |             -              |               CSS                | CSS,Stylus Sass,SCSS,Less |
|       **Project**       |
|      Dependencies       |          ✘           |          ✘           |              ✔               |             ✔             |          ✘           |             ✔              |               ✔                |          ✔           |             ✘              |                ✔                 |             ✔             |
|     Project Support     |          ✔           |          ✔           |              ✔               |             ✔             |          ✔           |             ✔              |               ✔                |          ✘           |             ✘              |                ✘                 |             ✔             |
|    Directory Support    |          ✔           |          ✘           |              ✔               |             ✘             |          ✘           |             ✔              |               ✘                |          ✘           |             ✘              |                ✘                 |             ✔             |
|       **Feature**       |
|          Price          |         Free         |         Free         |             Free             |           Free            |     Free & Paid      |            Free            |          Free & Paid           |         Free         |            Free            |               Paid               |           Free            |
|        Community        |          ✔           |          ✘           |              ✔               |             ✘             |          ✔           |             ✔              |               ✔                |          ✘           |             ✘              |                ✔                 |             ✔             |
|          Rate           |         ★★☆          |          ☆           |            ★★★★★             |           ★★★★            |         ★★☆          |           ★★★★☆            |              ★★★☆              |          ★★          |             ★☆             |               ★★☆                |           ★★★☆            |

## Online Code Editor

### **Thimble**

![thimble](./thimble.jpeg)

[Thimble](https://thimble.mozilla.org/) 是 Mozilla 旗下一款在线代码编辑器，可以借用 HTML、CSS 和 JavaScript 的能力轻松地创建和发布网页。但是 Thimble 即将下线，不再维护用户数据；用户的项目与账号将搬到 Glitch 中。Glitch 算是 Thimble 的一个升级款，详情移步 [Glitch](#Glitch).

### **Dabblet**

![dabblet](./dabblet.jpeg)

[Dabblet](http://dabblet.com/) 提供的能力非常有限，只适合简单的 Web Component & CSS 的调试使用。它对 CSS 模块的设计让人一头雾水。

### **Codesandbox**

![Codesandbox](./codesandbox.jpeg)

[Codesandbox](http://) 是一款很良心的在线 Editor，几乎能够覆盖平时开发需求。
它的社区提供了大量优质的 Demo 项目，可以随时 fork 到自己的环境进行修改和开发；同时官方也提供了大量的 Template 项目，包含但不仅限于：Angular、React、Vanilla、Vue、Gatsby、Next.js、Node、Next.js、React + TS、Vanilla + TS、CsJS、Dojo、Preact、Reason、Static、Svelte、Apollo、Ember、Gridsome、MDX Deck、Nest、Next.js、Node、VuePress、Staleguidist、Sapper；它还可以直接授权登录 Github，同步 Github 中的项目修改和提交。Codesandbox 也是 React 官方推崇的一款 Web Online Code Editor。
对于自己开发完的项目，也可以进行发布（三级域名的方式）。在远程协助方面，Codesandbox 也开放了 Live 的能力，使得它可能成为 Interview 或者结对编程的一个解决方案。总得来说，Codesandbox 最大程度地实现了 Local Client 的能力。

### **Playcode**

![Playcode](./playcode.jpeg)

[Playcode](https://playcode.io) 同样是一款值得夸赞的在线 Editor。极简的面板，没有过多的干扰信息。代码提示绝对是 playcode 的一个亮点。Code Snippet & Auto Complete 都最大程度了提高了开发效率。

### **Codepen**

![Codepen](./codepen.jpeg)

[Codepen](http://codepen.io) 也是 React 官方推荐的一款 Online Code Editor。三段式（HTML + CSS + JS）的设计，使它成为一个聚焦于组件开发领域以及代码块展示的利器。Codepen 的社区也有相当多的优秀案例可以 fork。当然它采用 CDNjs 的依赖处理方式，使用我们很难做更多的事。

### **Stackblitz**

![Stackblitz](./stackblitz.jpeg)

[Stackbliz](https://stackblitz.com/) 是一个在 [Github](https://github.com/stackblitz/core/) 上开源的产品。从它富有野心的 Slogan: Your local env,now in the Browser
以及 Online IDE powered by Visual Studio Code 可以看出，这就是一个 Web 版本的 VSCode. 实现了 VSCode 的很多能力。Stackbliz 是唯一一款可以正面硬刚 Codesandbox 的产品。

### **JSBin**

![JSBin](./jsbin.jpeg)

[JSBin](https://jsbin.com) 跟 Codepen 算是一对好基友了，能力都大致相同。在脚本开发语言上非常丰富，样式处理文件的支持上也相当给力。

### **Babeljs**

[Babeljs](https://babeljs.io/repl) 是一个由 Babel 官方推荐的编译测试 Playground。主要向用户展示 Babel 的能力。

### **TypeScript**

[TypeScript](https://www.typescriptlang.org/play/index.html) 则是一个由 TypeScript 官方推荐的编译测试 Playground。主要向用户展示 TypeScript 的能力。

### **CodeInterview**

Screen Test & Code Interivew

[CodeInterview](https://www.remoteinterview.io/) 是一款针对面试场景的行业解决方案，非付费版本功能有效，不予评价。

### **Glitch**

![Glitch](./glitch.jpeg)

[Glitch](https://glitch.com) 上同样有大量的优秀案例，可以 fork。在线编码以及及时反馈方面还需要优化。
