# Awesome Coc Extensions

[coc.nvim](https://github.com/neoclide/coc.nvim) is a plugin for neovim that aims to get a similar experience to vscode.

<!--ts-->
* [Awesome Coc Extensions](#awesome-coc-extensions)
* [Packages](#packages)
   * [Language Support](#language-support)
   * [Completion Enhanced](#completion-enhanced)
   * [Coc List extensions](#coc-list-extensions)
   * [Lint](#lint)
   * [Application](#application)
   * [SDK](#sdk)
   * [Formatter](#formatter)
   * [User Experience](#user-experience)
   * [Deprecated](#deprecated)
* [License](#license)

<!-- Created by https://github.com/ekalinin/github-markdown-toc -->
<!-- Added by: aerian, at: 2022年 09月 21日 星期三 12:56:08 CST -->

<!--te-->

# Packages

## Language Support

- [coc-angular](https://github.com/iamcco/coc-angular), a fork from [angular/vscode-ng-language-service](https://github.com/angular/vscode-ng-language-service), for `angular`.
- [coc-ansible](https://github.com/yaegassy/coc-ansible) for `yaml.ansible`, use [ansible-language-server](https://github.com/ansible/ansible-language-server) (scoped packages: `@yaegassy/coc-ansible`)
- [coc-blade](https://github.com/yaegassy/coc-blade) for `blade`, laravel blade templates extension. Provides "formatter", "linter", "completion" and more...
- [coc-clangd](https://github.com/clangd/coc-clangd) for C/C++/Objective-C, use [clangd](https://clangd.github.io)
- [coc-clang-format-style-options](https://www.npmjs.com/package/coc-clang-format-style-options) coc.nvim extension, helps you write `.clang-format` more easily.
- [coc-cmake](https://github.com/voldikss/coc-cmake) for cmake code completion
- [coc-css](https://github.com/neoclide/coc-css) for `css`, `scss` and `less`.
- [coc-cssmodules](https://github.com/antonk52/coc-cssmodules) css modules intellisense.
- [coc-deno](https://github.com/fannheyward/coc-deno) for [deno](https://github.com/denoland/deno), fork of [vscode_deno](https://github.com/denoland/vscode_deno).
- [coc-diagnostic](https://github.com/iamcco/coc-diagnostic) for All filetypes, use [diagnostic-languageserver](https://github.com/iamcco/diagnostic-languageserver).
- [coc-dash-complete](https://github.com/voldikss/coc-dash-complete) Press `-` to trigger buffer source completion.
- [coc-dot-complete](https://github.com/voldikss/coc-dot-complete) Press `.` to trigger buffer source completion.
- [coc-docker](https://github.com/josa42/coc-docker) for `dockerfile`.
- [coc-dlang](https://github.com/vushu/coc-dlang) for `d` code completion, based on [serve-d](https://github.com/Pure-D/serve-d).
- [coc-ecdict](https://github.com/fannheyward/coc-ecdict) ECDICT extension
- [coc-elixir](https://github.com/elixir-lsp/coc-elixir) for `elixir`, based on [elixir-ls](https://github.com/elixir-lsp/elixir-ls/).
- [coc-ember](https://github.com/NullVoxPopuli/coc-ember) for ember projects. Wraps [@lifeart](https://github.com/lifeart)'s [ember-language-server](https://github.com/lifeart/ember-language-server)
- [coc-glint](https://github.com/NullVoxPopuli/coc-glint) for typed ember projects. Wraps [typed-ember](https://github.com/typed-ember)'s [glint-language-server](https://github.com/typed-ember/glint/tree/main/packages/core/bin)
- [coc-erlang_ls](https://github.com/hyhugh/coc-erlang_ls) for `erlang`, based on [erlang_ls](https://github.com/erlang-ls/erlang_ls)
- [coc-esbonio](https://github.com/yaegassy/coc-esbonio) for `rst` (reStructuredText), [esbonio](https://pypi.org/project/esbonio/) ([Sphinx] Python Documentation Generator) language server extension.
- [coc-flow](https://github.com/amiralies/coc-flow) for [`flow`](https://flow.org)
- [coc-flutter](https://github.com/iamcco/coc-flutter) for [`flutter`](https://github.com/flutter/flutter)
- [coc-fsharp](https://github.com/yatli/coc-fsharp) for `fsharp`.
- [coc-glslx](https://github.com/Eric-Song-Nop/coc-glslx) for `glsl`, use [glslx](https://github.com/evanw/glslx).
- [coc-go](https://github.com/josa42/coc-go) for `go`, use [gopls](https://github.com/golang/tools/tree/master/gopls).
- [coc-graphql](https://github.com/felippepuhle/coc-graphql) for `graphql`.
- [coc-haxe](https://github.com/vantreeseba/coc-haxe) for `haXe`
- [coc-html](https://github.com/neoclide/coc-html) for `html`, `handlebars` and `razor`.
- [coc-htmldjango](https://github.com/yaegassy/coc-htmldjango) for `htmldjango`, django templates (htmldjango) extension. Provides "formatter", "linter" and more...
- [coc-htmlhint](https://github.com/yaegassy/coc-htmlhint) for `html`, Integrates the HTMLHint static analysis tool.
- [coc-html-css-support](https://github.com/yaegassy/coc-html-css-support) for HTML id and class attribute completion.
- [coc-intelephense](https://github.com/yaegassy/coc-intelephense) for php, fork of [vscode-intelephense](https://github.com/bmewburn/vscode-intelephense). (scoped packages: `@yaegassy/coc-intelephense`)
- [coc-java](https://github.com/neoclide/coc-java) for `java`, use [eclipse.jdt.ls](https://github.com/eclipse/eclipse.jdt.ls).
- [coc-jedi](https://github.com/pappasam/coc-jedi) for `python`, use [jedi-language-server](https://github.com/pappasam/jedi-language-server).
- [coc-json](https://github.com/neoclide/coc-json) for `json`.
- [coc-julia](https://github.com/fannheyward/coc-julia) for [`julia`](https://julialang.org/).
- [coc-lightbulb](https://github.com/xiyaowong/coc-lightbulb-) Code action 💡 for coc.nvim
- [coc-lsp-wl](https://github.com/voldikss/coc-lsp-wl) for `wolfram mathematica`, fork of [vscode-lsp-wl](https://github.com/kenkangxgwe/vscode-lsp-wl).
- [coc-ltex](https://valentjn.github.io/ltex/vscode-ltex/installation-usage-coc-ltex.html) grammar/spell checker
- [coc-markdown-preview-enhanced](https://github.com/weirongxu/coc-markdown-preview-enhanced) [Markdown Preview Enhanced](https://shd101wyy.github.io/markdown-preview-enhanced/) for coc.nvim
- [coc-markmap](https://github.com/gera2ld/coc-markmap) [markdown + mindmap](https://markmap.js.org/) for coc.nvim
- [coc-nginx](https://github.com/yaegassy/coc-nginx) for `nginx`, use [nginx-language-server](https://github.com/pappasam/nginx-language-server) and [nginxfmt](https://pypi.org/project/nginxfmt/) (scoped packages: `@yaegassy/coc-nginx`)
- [coc-omnisharp](https://github.com/yatli/coc-omnisharp) for `csharp` and `visualbasic`.
- [coc-perl](https://github.com/ryuta69/coc-perl) for `perl`.
- [coc-phpactor](https://github.com/phpactor/coc-phpactor) for `php`, using [phpactor](https://github.com/phpactor/phpactor)
- [coc-phpls](https://github.com/marlonfan/coc-phpls) for `php`, use [intelephense-docs](https://github.com/bmewburn/intelephense-docs).
- [coc-phpstan](https://github.com/yaegassy/coc-phpstan) for `php`, use [phpstan](https://github.com/phpstan/phpstan) (scoped packages: `@yaegassy/coc-phpstan`)
- [coc-php-cs-fixer](https://github.com/yaegassy/coc-php-cs-fixer) for `php`, [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) and [Laravel Pint](https://github.com/laravel/pint) extension.
- [coc-psalm](https://github.com/yaegassy/coc-psalm) for `php`, use [psalm](https://psalm.dev/) language server.
- [coc-powershell](https://github.com/yatli/coc-powershell) for PowerShellEditorService integration.
- [coc-prisma](https://github.com/pantharshit00/coc-prisma) for Prisma schema integration.
- [coc-pydocstring](https://github.com/yaegassy/coc-pydocstring) for `python`, using [doq](https://pypi.org/project/doq/) (python docstring generator) extension.
- [coc-pylsp](https://github.com/yaegassy/coc-pylsp) for `python`, use [pylsp(python-lsp-server)](https://github.com/python-lsp/python-lsp-server). (scoped packages: `@yaegassy/coc-pylsp`)
- [coc-pyright](https://github.com/fannheyward/coc-pyright) for `python`, [Pyright](https://github.com/microsoft/pyright) extension
- [coc-python](https://github.com/neoclide/coc-python) for `python`, extension forked from [vscode-python](https://github.com/Microsoft/vscode-python). *(Not maintained anymore)*
- [coc-r-lsp](https://github.com/neoclide/coc-r-lsp) for `r`, use [R languageserver](https://github.com/REditorSupport/languageserver).
- [coc-reason](https://github.com/jaredly/reason-language-server/tree/master/editor-extensions/coc.nvim) for [`reasonml`](https://reasonml.github.io/)
- [coc-rls](https://github.com/neoclide/coc-rls) for `rust`, use [Rust Language Server](https://github.com/rust-lang/rls)
- [coc-rome](https://github.com/fannheyward/coc-rome) for `javascript`, `typescript`, `json` and more, use [`Rome`](https://github.com/romefrontend/rome)
- [coc-rust-analyzer](https://github.com/fannheyward/coc-rust-analyzer) for `rust`, use [rust-analyzer](https://github.com/rust-analyzer/rust-analyzer)
- [coc-sh](https://github.com/josa42/coc-sh) for `bash` using [bash-language-server](https://github.com/bash-lsp/bash-language-server).
- [coc-stylelintplus](https://github.com/bmatcuk/coc-stylelintplus) for linting CSS and CSS preprocessed formats
- [coc-snippets](https://github.com/neoclide/coc-snippets) provides snippets solution.
- [coc-solargraph](https://github.com/neoclide/coc-solargraph) for `ruby`, use [solargraph](http://solargraph.org/).
- [coc-solidity](https://github.com/qiuxiang/coc-solidity) for [solidity](https://docs.soliditylang.org/)
- [coc-sourcekit](https://github.com/klaaspieter/coc-sourcekit) for [`Swift`](https://swift.org/)
- [coc-spell-checker](https://github.com/iamcco/coc-spell-checker) A basic spell checker that works well with camelCase code
- [coc-sql](https://github.com/fannheyward/coc-sql) for `sql`.
- [coc-sqlfluff](https://github.com/yaegassy/coc-sqlfluff) for `sql`, [SQLFluff](https://pypi.org/project/sqlfluff/) (A SQL linter and auto-formatter for Humans) extension
- [coc-sumneko-lua](https://github.com/xiyaowong/coc-sumneko-lua) Lua extension using sumneko lua-language-server
- [coc-svelte](https://github.com/coc-extensions/coc-svelte) for [`svelte`](https://github.com/sveltejs/svelte).
- [coc-svg](https://github.com/iamcco/coc-svg) for `svg`.
- [coc-symbol-line](https://github.com/xiyaowong/coc-symbol-line) Symbols outline for coc.nvim.
- [coc-tabnine](https://github.com/neoclide/coc-tabnine) for [tabnine](https://tabnine.com/).
- [coc-tailwindcss](https://github.com/iamcco/coc-tailwindcss) for `tailwindcss`.
- [coc-tailwindcss3](https://github.com/yaegassy/coc-tailwindcss3) for `tailwindcss`. (scoped packages: `@yaegassy/coc-tailwindcss3`).
- [coc-texlab](https://github.com/fannheyward/coc-texlab) for `LaTeX` using [TexLab](https://texlab.netlify.com/).
- [coc-thrift-syntax-support](https://github.com/cposture/coc-thrift-syntax-support) for `thrift`.
- [coc-toml](https://github.com/kkiyama117/coc-toml) for [`toml`](https://github.com/toml-lang/toml) using [taplo](https://github.com/tamasfe/taplo).
- [coc-tsserver](https://github.com/neoclide/coc-tsserver) for `javascript` and `typescript`.
- [coc-vetur](https://github.com/neoclide/coc-vetur) for `vue`, use [vetur](https://github.com/vuejs/vetur).
- [coc-volar](https://github.com/yaegassy/coc-volar) for `vue`, use [volar](https://github.com/johnsoncodehk/volar). (scoped packages: `@yaegassy/coc-volar`).
- [coc-vimlsp](https://github.com/iamcco/coc-vimlsp) for `viml`.
- [coc-xml](https://github.com/fannheyward/coc-xml) for `xml`, use [lsp4xml](https://github.com/angelozerr/lsp4xml).
- [coc-yaml](https://github.com/neoclide/coc-yaml) for `yaml`
- [coc-zig](https://github.com/UltiRequiem/coc-zig) for `zig` files.
- [coc-zls](https://github.com/xiyaowong/coc-zls) zls extension, for `zig`

## Completion Enhanced

- [coc-just-complete](https://github.com/voldikss/coc-just-complete) Press `_` to trigger buffer source completion.
- [coc-emmet](https://github.com/neoclide/coc-emmet) provides emmet suggestions in completion list.
- [coc-browser](https://github.com/voldikss/coc-browser) for browser words completion
- [coc-calc](https://github.com/weirongxu/coc-calc) expression calculation extension

## Coc List extensions

- [coc-fzf-preview](https://github.com/yuki-ycino/fzf-preview.vim/) provide powerful [fzf](https://github.com/junegunn/fzf) integration.
- [coc-lists](https://github.com/neoclide/coc-lists) provides some basic lists like fzf.vim.
- [coc-marketplace](https://github.com/fannheyward/coc-marketplace), coc.nvim extensions marketplace.

## Lint

- [coc-cfn-lint](https://github.com/joenye/coc-cfn-lint) for CloudFormation Linter, [cfn-python-lint](https://github.com/aws-cloudformation/cfn-python-lint)
- [coc-markdownlint](https://github.com/fannheyward/coc-markdownlint) for markdown linting
- [coc-stylelint](https://github.com/neoclide/coc-stylelint) for linting CSS and CSS preprocessed formats
- [coc-stylua](https://github.com/xiyaowong/coc-stylua) Stylua(lua formatter) extension
- [coc-eslint](https://github.com/neoclide/coc-eslint) Eslint extension for coc.nvim

## Application

- [coc-explorer](https://github.com/weirongxu/coc-explorer) File Explorer extension
- [coc-git](https://github.com/neoclide/coc-git) provides git integration.
- [coc-gist](https://github.com/voldikss/coc-gist) gist management
- [coc-discord](https://github.com/amiralies/coc-discord) discord rich presence for coc.nvim

## SDK

- [coc-discord-rpc](https://github.com/LeonardSSH/coc-discord-rpc) fully customizable discord rpc integration with support for over 130+ of the most popular languages
- [coc-webview](https://github.com/weirongxu/coc-webview) Using an external browser to support the webview.

## Formatter

- [coc-golines](https://github.com/xiyaowong/coc-golines) golines(go formatter) extension
- [coc-prettier](https://github.com/neoclide/coc-prettier) a fork of [prettier-vscode](https://github.com/prettier/prettier-vscode).

## User Experience

- [coc-swagger](https://github.com/haishanh/coc-swagger) for improved Swagger/OpenAPI spec authoring experience.
- [coc-translator](https://github.com/voldikss/coc-translator) language transaction extension
- [coc-yank](https://github.com/neoclide/coc-yank) provides yank highlights & history.
- [coc-highlight](https://github.com/neoclide/coc-highlight) provides default document symbol highlighting and color support.

## Deprecated

- [coc-metals](https://github.com/scalameta/coc-metals) for Scala using [`Metals`](http://scalameta.org/metals/), but not support the version being 0.11.2.
- [coc-floaterm](https://github.com/voldikss/coc-floaterm) for [vim-floaterm](https://github.com/voldikss/vim-floaterm) integration. (Archived)
- [coc-tasks](https://github.com/voldikss/coc-tasks) for [asynctasks.vim](https://github.com/skywind3000/asynctasks.vim) integration

# License

MIT
