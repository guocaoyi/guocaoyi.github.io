---
layout: post
title: Online Code Editor
date: 2019-04-03 14:06:18
tags: env
categories:
  - Demo
---

# 聊一聊 Web Online Code Editor

便捷性：IDE < Editor < Web Online Code Editor
使用成本：IDE > Editor > Web Online Code Editor

关于这个问题，知乎上有个答案我很认可：『IDE 和 Editor 是包含和被包含的关系，IDE 内置了 Editor』。
但是只 Atom 和 VSCode 等产品出现后，改变了这一现状。

<!-- more -->

IDE 帮我们处理了很多事情：创建文档索引缓存、Code Snippet、Autocomplete、Debug、依赖管理等等；但是 IDE 的使用成本时很高的；
项目管理、版本控制、代码跳转、Dubug
代码高亮、调试、运行;
配置 + 插件去整合开发环境
侧重：开发

Editor 在文档编辑的基础上，引用插件的机制在一定程度上让我们降低了 Code Edit 的成本；
插件去整合开发环境
侧重：编辑代码

Online Code Editor 算多是一种 Draft；快速实现、验证想法；
侧重：草稿

## Feature

|           Production            | Highlighting | ErrorChecking | Formatting | AutoCompletion | Debugging | ES Compiler | TS Compiler | Dependencies | Project Support | Directory Support |
| :-----------------------------: | :----------: | :-----------: | :--------: | :------------: | :-------: | :---------: | :---------: | :----------: | :-------------: | :---------------: |
|       [Thimble](#Thimble)       |      ✔       |       ✘       |     ✘      |       ✔        |     ✘     |      ✘      |      ✘      |      ✘       |        ✔        |         ✔         |
|       [Dabblet](#Dabblet)       |      ✘       |       ✘       |     ✘      |       ✘        |     ✘     |      ✘      |      ✘      |      ✘       |        ✔        |         ✘         |
|   [CodeSandbox](#Codesandbox)   |      ✔       |       ✔       |     ✔      |       ✔        |     ✘     |      ✔      |      ✔      |      ✔       |        ✔        |         ✔         |
|      [Playcode](#Playcode)      |              |               |            |                |           |             |             |              |                 |                   |
|       [Codepen](#Codepen)       |              |               |            |                |           |             |             |              |                 |                   |
|    [Stackblitz](#Stackblitz)    |              |               |            |                |           |             |             |              |                 |                   |
|         [JSBin](#JSBin)         |              |               |            |                |           |             |             |              |                 |                   |
|       [Babeljs](#Babeljs)       |              |               |            |                |           |             |             |              |                 |                   |
|    [TypeScript](#TypeScript)    |              |               |            |                |           |             |             |              |                 |                   |
| [CodeInterview](#CodeInterview) |              |               |            |                |           |             |             |              |                 |                   |

## Online Code Editor

### Thimble

![thimble](./thimble.jpeg)

- 推荐指数：★★★☆
- 付费情况：Free

[Thimble](https://thimble.mozilla.org/) 是 Mozilla 旗下一个在线代码编辑器，可以很轻松地创建和发布网页， 借用 HTML、CSS 和 JavaScript 的能力。它的项目代码托管在 Glitch 中

### Dabblet

![dabblet](./dabblet.jpeg)

- 推荐指数：★★☆
- 付费情况：Free

### Codesandbox

![Codesandbox](./codesandbox.jpeg)

- 推荐指数：★★★☆
- 付费情况：Free

[Codesandbox](http://)一款很良心的在线 Editor，几乎能够覆盖平时开发需求；如果非要说缺憾的，那么可能只有代码高亮了；
当然 AutoComplete & HighLight 未能达到。

### Playcode

![Playcode](./playcode.jpeg)

- 推荐指数：★★★☆
- 付费情况：Free

这款 Editor 算是 Codesandbox plus 版本；具备了 Autocomplete & HighLight 的能力；实在良心

### Codepen

![Codepen](./codepen.jpeg)

- 推荐指数：★★★☆
- 付费情况：Free

### Stackblitz

![Stackblitz](./stackblitz.jpeg)

- 推荐指数：★★★★★
- 付费情况：Free

[Stackbliz](https://stackblitz.com/) 是一个在 [Github](https://github.com/stackblitz/core/) 上开源的产品。从他们的 Slogan: Your local env,now in the Browser
以及 Online IDE powered by Visual Studio Code 可以看出，这就是一个 Web 版本的 VSCode. 实现了 VSCode 的很多能力。

Feature

### JSBin

![JSBin](./jsbin.jpeg)

- 推荐指数：★★☆
- 付费情况：Free

### Babeljs

- 推荐指数：★★★
- 付费情况：Free

[Babeljs](https://babeljs.io/repl) 是一个由 Babel 官方推荐

### TypeScript

- 推荐指数：★★★
- 付费情况：Free

### CodeInterview

- 推荐指数：★★★☆
- 付费情况：Paid
  CodeInterview 是一款行业解决方案；主要针对面试邀约场景下的远程编程；需要付费
