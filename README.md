# cxa / realazy

[中文](#中文)

I build small, practical software across Apple platforms, Emacs, Web/UI tooling, and F#/OCaml/Reason language and data-processing experiments.

### Apps and Desktop Tools

- [yifan](https://github.com/cxa/yifan) - A React Native client for Fanfou/饭否, with a reusable `rn-fanfou-client` package.
- [XVDL](https://github.com/cxa/xvdl) - macOS Safari extension for downloading authorized X/Twitter videos.
- [kitty-imove](https://github.com/cxa/kitty-imove) - Interactive window-moving overlay for kitty terminal, close to kitty's built-in resize mode.
- [dicmd](https://github.com/cxa/dicmd) - Command-line interface for macOS Dictionary.app.
- [dicsrv](https://github.com/cxa/dicsrv) - HTTP service wrapper around macOS Dictionary.app.
- [chatgpt](https://github.com/cxa/chatgpt) - Lightweight terminal wrapper for ChatGPT. 📦 Archived.

### Emacs and Editor Tooling

- [lsp-biome](https://github.com/cxa/lsp-biome) - `lsp-mode` client for Biome.
- [agent-shell-macext](https://github.com/cxa/agent-shell-macext) - macOS enhancements for `agent-shell`, including Finder file yanking, drag and drop, and native notifications.
- [moonbit-mode](https://github.com/cxa/moonbit-mode) - Emacs major mode for MoonBit.
- [eglot-lspx](https://github.com/cxa/eglot-lspx) - Run multiple LSP servers in Eglot through `lspx`.
- [eaglet](https://github.com/cxa/eaglet) - Small additions around Emacs Eglot workflows.
- [cape-tailwindcss](https://github.com/cxa/cape-tailwindcss) - CAPF completion source for Tailwind CSS class names.
- [microtext-refinement](https://github.com/cxa/microtext-refinement) - Emacs text-refinement tool powered by `gptel`.
- [ob-C-stdin](https://github.com/cxa/ob-C-stdin) - Adds `:stdin` support to Org Babel C/C++/D code blocks.
- [ob-js-node-eval](https://github.com/cxa/ob-js-node-eval) - Node-based result evaluation for `org-babel-js`.
- [ob-js-osascript](https://github.com/cxa/ob-js-osascript) - Org Babel support for JavaScript-flavored AppleScript (`osascript`).
- [ob-awk-cmd](https://github.com/cxa/ob-awk-cmd) - Org Babel helper for selecting AWK variants through a `:cmd` header.

### Web and UI Utilities

- [astro-inline-svg](https://github.com/cxa/astro-inline-svg) - Inline SVGs directly into Astro templates.
- [enough-shadcn-ui-colors](https://github.com/cxa/enough-shadcn-ui-colors) - Color schemes for shadcn/ui projects.
- [11n-shades](https://github.com/cxa/11n-shades) - Palette generator for interface color systems.
- [uilabs](https://github.com/cxa/uilabs) - realazy's UI labs and frontend experiments.
- [twx](https://github.com/cxa/twx) - Tiny `tailwind-merge` + `clsx` helper.
- [live-reload-server](https://github.com/cxa/live-reload-server) - Dependency-free Python static file server with live reload for no-build HTML/CSS/JS projects.

### Apple Platform Libraries

- [MenuItemKit](https://github.com/cxa/MenuItemKit) - UIMenuItem with image support and closure-based actions. 📦 Archived, but still the most widely used project here.
- [Piz](https://github.com/cxa/Piz) - Minimal Swift unzipper designed to just work.
- [Mvce](https://github.com/cxa/Mvce) - Event-driven MVC glue for UIKit/AppKit: simple, lightweight, and unobtrusive. 📦 Archived.
- [AppExtensionCommunicator](https://github.com/cxa/AppExtensionCommunicator) - Swift framework for communication between an app extension and its containing app.
- [CXAHyperlinkLabel](https://github.com/cxa/CXAHyperlinkLabel) - UILabel replacement with block-based link tap and long-press handling.
- [KissNSUserDefaults](https://github.com/cxa/KissNSUserDefaults) - Property-style NSUserDefaults access without subclassing.
- [KissNSUbiquitousKeyValueStore](https://github.com/cxa/KissNSUbiquitousKeyValueStore) - Property-style wrapper for NSUbiquitousKeyValueStore.
- [CXADirectoryContentsWatcher](https://github.com/cxa/CXADirectoryContentsWatcher) - Watch a directory when files are added or removed.
- [DOMContentLoadedDelegate](https://github.com/cxa/DOMContentLoadedDelegate) - Small helper for accessing UIWebView DOM as early as possible. 📦 Archived.
- [WebViewContentPositioner](https://github.com/cxa/WebViewContentPositioner) - Preserve and restore UIWebView scroll position. 📦 Archived.
- [NonConsumableIAPHelper](https://github.com/cxa/NonConsumableIAPHelper) - Lightweight wrapper for non-consumable In-App Purchase. 📦 Archived.
- [XPaver](https://github.com/cxa/XPaver) - Make XPath-based XML navigation easier.
- [HaodooPDB](https://github.com/cxa/HaodooPDB) - Extract contents from Haodoo PDB ebook files.

### F#, OCaml, Reason, and Data Libraries

- [Fpub](https://github.com/cxa/Fpub) - F#/.NET Standard library for reading EPUB files.
- [Mu](https://github.com/cxa/Mu) - Elm Architecture-inspired Xamarin pattern experiment, designed to be simple and unobtrusive. 📦 Archived.
- [KeyPathJson](https://github.com/cxa/KeyPathJson) - Safe key-path JSON navigator for `System.Json`.
- [JPath](https://github.com/cxa/JPath) - Key-path navigation for `JsonElement`.
- [bs-containers-core](https://github.com/cxa/bs-containers-core) - OCaml containers core for BuckleScript. 📦 Archived.
- [bs-json-keypather](https://github.com/cxa/bs-json-keypather) - Key-path JSON navigator for BuckleScript. 📦 Archived.
- [ppx_bsx](https://github.com/cxa/ppx_bsx) - OCaml JSX syntax extension for ReasonReact. 📦 Archived.
- [JsonR](https://github.com/cxa/JsonR) - BuckleScript JSON helper built around `Result`. 📦 Archived.

### Historical and Deprecated Projects

- [UIMenuItem-CXAImageSupport](https://github.com/cxa/UIMenuItem-CXAImageSupport) - Earlier Objective-C image-backed UIMenuItem support, later replaced by MenuItemKit.
- [CXAAutoRemovalNotification](https://github.com/cxa/CXAAutoRemovalNotification) - Tool for reducing NSNotificationCenter boilerplate; deprecated.
- [HalfTea](https://github.com/cxa/HalfTea) - Earlier TEA/Xamarin experiment, later continued by Mu.
- [Reducer.swift](https://github.com/cxa/Reducer.swift) - Small Swift experiment inspired by `React.useReducer`.
- [vscode-elmx](https://github.com/cxa/vscode-elmx) - Visual Studio Code extension for `elmx`.
- [elm-app-starter-kit](https://github.com/cxa/elm-app-starter-kit) - Elm app starter kit with webpack and hot reload.
- [reason-react-webpack-starter-kit](https://github.com/cxa/reason-react-webpack-starter-kit) - ReasonReact webpack starter kit.

More code and experiments live in [github.com/cxa?tab=repositories](https://github.com/cxa?tab=repositories).

---

<a id="中文"></a>

我主要写一些小而实用的软件：Apple 平台应用与库、Emacs 工具、Web/UI 小工具，以及 F#/OCaml/Reason 方向的语言与数据处理实验。

### 应用与桌面工具

- [yifan](https://github.com/cxa/yifan) - 一饭，饭否的 React Native 客户端，并内置可复用的 `rn-fanfou-client` 包。
- [XVDL](https://github.com/cxa/xvdl) - macOS Safari 扩展，用于下载有授权的 X/Twitter 视频。
- [kitty-imove](https://github.com/cxa/kitty-imove) - kitty 终端的交互式窗口移动 overlay，体验接近内置 resize mode。
- [dicmd](https://github.com/cxa/dicmd) - macOS Dictionary.app 的命令行工具。
- [dicsrv](https://github.com/cxa/dicsrv) - macOS Dictionary.app 的 HTTP 服务封装。
- [chatgpt](https://github.com/cxa/chatgpt) - 轻量的终端 ChatGPT 包装脚本。📦 已归档。

### Emacs 与编辑器工具

- [lsp-biome](https://github.com/cxa/lsp-biome) - Biome 的 `lsp-mode` 客户端。
- [agent-shell-macext](https://github.com/cxa/agent-shell-macext) - `agent-shell` 的 macOS 增强：Finder 文件粘贴、拖放、原生通知等。
- [moonbit-mode](https://github.com/cxa/moonbit-mode) - MoonBit 的 Emacs major mode。
- [eglot-lspx](https://github.com/cxa/eglot-lspx) - 通过 `lspx` 在 Eglot 中运行多个 LSP server。
- [eaglet](https://github.com/cxa/eaglet) - 围绕 Emacs Eglot 工作流的小型增强。
- [cape-tailwindcss](https://github.com/cxa/cape-tailwindcss) - Tailwind CSS class name 的 CAPF 补全源。
- [microtext-refinement](https://github.com/cxa/microtext-refinement) - 基于 `gptel` 的 Emacs 文本润色工具。
- [ob-C-stdin](https://github.com/cxa/ob-C-stdin) - 为 Org Babel 的 C/C++/D 代码块补上 `:stdin` 支持。
- [ob-js-node-eval](https://github.com/cxa/ob-js-node-eval) - 用 Node 计算 `org-babel-js` 的代码块结果。
- [ob-js-osascript](https://github.com/cxa/ob-js-osascript) - 支持 JavaScript 风格 AppleScript (`osascript`) 的 Org Babel 扩展。
- [ob-awk-cmd](https://github.com/cxa/ob-awk-cmd) - 通过 `:cmd` header 动态选择 AWK 变体的 Org Babel 扩展。

### Web 与 UI 工具

- [astro-inline-svg](https://github.com/cxa/astro-inline-svg) - 在 Astro 模板中直接内联 SVG。
- [enough-shadcn-ui-colors](https://github.com/cxa/enough-shadcn-ui-colors) - 给 shadcn/ui 项目使用的一组配色方案。
- [11n-shades](https://github.com/cxa/11n-shades) - 面向界面色彩系统的 palette 生成器。
- [uilabs](https://github.com/cxa/uilabs) - realazy 的 UI labs 和前端实验集合。
- [twx](https://github.com/cxa/twx) - 很小的 `tailwind-merge` + `clsx` 辅助函数。
- [live-reload-server](https://github.com/cxa/live-reload-server) - 无外部依赖的 Python 静态文件服务器，适合 no-build HTML/CSS/JS 项目自动刷新。

### Apple 平台库

- [MenuItemKit](https://github.com/cxa/MenuItemKit) - 支持图片和 closure action 的 UIMenuItem。📦 已归档，但仍是这里使用最广的项目。
- [Piz](https://github.com/cxa/Piz) - 极简 Swift unzipper，目标是直接好用。
- [Mvce](https://github.com/cxa/Mvce) - UIKit/AppKit 的事件驱动 MVC 胶水层，尽量保持简单、轻量、不侵入。📦 已归档。
- [AppExtensionCommunicator](https://github.com/cxa/AppExtensionCommunicator) - app extension 与 containing app 之间通信的 Swift framework。
- [CXAHyperlinkLabel](https://github.com/cxa/CXAHyperlinkLabel) - UILabel 替代组件，支持 block 形式处理链接点击和长按。
- [KissNSUserDefaults](https://github.com/cxa/KissNSUserDefaults) - 用 property 风格访问 NSUserDefaults，不需要 subclass。
- [KissNSUbiquitousKeyValueStore](https://github.com/cxa/KissNSUbiquitousKeyValueStore) - NSUbiquitousKeyValueStore 的 property 风格封装。
- [CXADirectoryContentsWatcher](https://github.com/cxa/CXADirectoryContentsWatcher) - 监听目录中文件的新增和删除。
- [DOMContentLoadedDelegate](https://github.com/cxa/DOMContentLoadedDelegate) - 尽早访问 UIWebView DOM 的小型工具。📦 已归档。
- [WebViewContentPositioner](https://github.com/cxa/WebViewContentPositioner) - 保存并恢复 UIWebView 滚动位置。📦 已归档。
- [NonConsumableIAPHelper](https://github.com/cxa/NonConsumableIAPHelper) - 非消耗型 In-App Purchase 的轻量封装。📦 已归档。
- [XPaver](https://github.com/cxa/XPaver) - 让基于 XPath 的 XML 导航更顺手。
- [HaodooPDB](https://github.com/cxa/HaodooPDB) - 提取好读 PDB 电子书格式内容的工具。

### F#、OCaml、Reason 与数据处理库

- [Fpub](https://github.com/cxa/Fpub) - 用 F#/.NET Standard 编写的 EPUB 读取库。
- [Mu](https://github.com/cxa/Mu) - 受 Elm Architecture 启发的 Xamarin 模式实验，追求简单且不侵入。📦 已归档。
- [KeyPathJson](https://github.com/cxa/KeyPathJson) - `System.Json` 的安全 key-path JSON navigator。
- [JPath](https://github.com/cxa/JPath) - `JsonElement` 的 key-path 导航工具。
- [bs-containers-core](https://github.com/cxa/bs-containers-core) - 面向 BuckleScript 的 OCaml containers core。📦 已归档。
- [bs-json-keypather](https://github.com/cxa/bs-json-keypather) - BuckleScript 的 key-path JSON 导航库。📦 已归档。
- [ppx_bsx](https://github.com/cxa/ppx_bsx) - ReasonReact 使用的 OCaml JSX 语法扩展。📦 已归档。
- [JsonR](https://github.com/cxa/JsonR) - 围绕 `Result` 设计的 BuckleScript JSON helper。📦 已归档。

### 历史项目与已弃用项目

- [UIMenuItem-CXAImageSupport](https://github.com/cxa/UIMenuItem-CXAImageSupport) - 早期 Objective-C 版本的图片 UIMenuItem 支持，后来由 MenuItemKit 取代。
- [CXAAutoRemovalNotification](https://github.com/cxa/CXAAutoRemovalNotification) - 减少 NSNotificationCenter 模板代码的工具，已弃用。
- [HalfTea](https://github.com/cxa/HalfTea) - 较早的 TEA/Xamarin 实验，后续由 Mu 延续。
- [Reducer.swift](https://github.com/cxa/Reducer.swift) - 受 `React.useReducer` 启发的 Swift 小实验。
- [vscode-elmx](https://github.com/cxa/vscode-elmx) - 面向 `elmx` 的 Visual Studio Code 扩展。
- [elm-app-starter-kit](https://github.com/cxa/elm-app-starter-kit) - 带 webpack 和 hot reload 的 Elm app starter kit。
- [reason-react-webpack-starter-kit](https://github.com/cxa/reason-react-webpack-starter-kit) - ReasonReact webpack starter kit。

更多代码和实验项目见 [github.com/cxa?tab=repositories](https://github.com/cxa?tab=repositories)。
