## .github目录结构及作用

`.github` 目录通常在一个 GitHub 项目中使用，用于存放 GitHub 提供的一些特性和工具的配置文件。以下是 .github 目录中可能包含的一些文件或子目录：

### workflows文件夹

这个目录用于存放 GitHub Actions 的工作流配置文件。GitHub Actions 是 GitHub提供的一种持续集成/持续部署 (CI/CD) 服务。用户可以定义工作流 (workflows)来自动化他们的软件开发工作，比如自动测试、自动构建和自动部署。

https://docs.github.com/zh/actions/using-workflows/about-workflows



看这个就行👉 **[关于工作流程的 YAML 语法](https://docs.github.com/zh/actions/using-workflows/workflow-syntax-for-github-actions#about-yaml-syntax-for-workflows)**  👈



### ISSUE_TEMPLATE文件夹

这个目录用于创建 issue 模板。这些模板会在用户新建一个 issue 时显示，可以帮助用户提供详细的报告或请求。

https://docs.github.com/zh/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file



https://docs.github.com/zh/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository



### PULL_REQUEST_TEMPLATE文件夹

这个目录用于创建 pull request 模板。这些模板会在用户新建一个 pull request 时显示，可以帮助用户提供详细的改动说明。

https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/using-query-parameters-to-create-a-pull-request



### FUNDING.yml文件

这个文件可以让项目的维护者指定他们接受捐款的方式。这个文件的内容会在用户点击 GitHub 项目页面上的 “Sponsor” 按钮时显示。

https://docs.github.com/zh/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/displaying-a-sponsor-button-in-your-repository



### CODEOWNERS文件

这个文件用于定义代码所有权。在这个文件中，你可以指定某个或某些 GitHub 用户为某个或某些文件的“所有者”。当这些文件在一个 pull request 中被修改时，这些用户会自动被设为该 pull request 的审查者。

https://docs.github.com/zh/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners



### dependabot.yml文件 或者 dependabot目录

这个文件或目录用于配置 Dependabot。Dependabot 是一个可以自动检查你的项目依赖是否有新版本或安全更新的工具。

https://docs.github.com/zh/code-security/dependabot/dependabot-version-updates/configuration-options-for-the-dependabot.yml-file




## 最后说明

以上是 .github 目录的一些常见用途。这个目录可以帮助开发者更好地管理他们的项目和社区。不过，所有这些文件和目录都是可选的，具体要不要使用以及如何使用，完全取决于项目的实际需求。



## 其他

**src 目录**：源码文件

**docs 目录**：项目文档

**public 目录**：公共资源或静态文件

**dist 目录**：项目的构建输出或分发版本。通常是存放经过编译、打包或压缩处理后的最终生成物。

**examples 目录**：示例文件

**test 目录**：测试文件



**LICENSE.txt**：授权协议

**README.md**： 自述文件，整个项目的简介使用方法等

**CHANGELOG.md**：日志

**.gitignore**：告诉git哪些文件不要进行跟踪，避免上传到GitHub



## git commit type

`feat` 新增特性 (feature)

`fix` 修复 Bug(bug fix) 

`docs` 修改文档 (documentation) 

`style` 代码格式修改(white-space, formatting, missing semi colons, etc) 

`refactor` 代码重构(refactor) 

`perf` 改善性能(A code change that improves performance) 

`test` 测试(when adding missing tests) 

`build` 变更项目构建或外部依赖（例如 scopes: webpack gulp、npm 等） 

`ci` 更改持续集成软件的配置文件和 package 中的 scripts 命令，例如 scopes: Travis, Circle 等 

`chore` 变更构建流程或辅助工具(比如更改测试环境) 

`revert` 代码回退