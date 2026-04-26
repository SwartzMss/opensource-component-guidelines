# OpenSource Component Guidelines

一个基于 `MkDocs Material` 的开源组件治理与 License 合规文档仓库。

## 内容方向

- 开源组件使用规范
- 常见 License 介绍与差异说明
- 商用、修改、分发、闭源等边界判断
- 合规流程、检查清单与模板
- 典型场景案例与第三方声明示例

## 文档结构

- 站点内容位于 `docs/`
- 站点配置位于 `mkdocs.yml`
- 文档依赖位于 `requirements-docs.txt`
- 自动部署配置位于 `.github/workflows/deploy-docs.yml`

## 部署方式

仓库已配置为在 `main` 分支有提交时，通过 GitHub Actions 自动构建并部署到 `gh-pages` 分支。

如果仓库的 GitHub Pages 已设置为从 `gh-pages` 分支发布，就不需要在本地手动生成最终文档。

## 使用方式

你只需要维护 `docs/` 下的文档内容，并在 GitHub 上提交到 `main` 分支。

每次提交后，GitHub Actions 会自动完成文档构建与 Pages 发布。

## 文档入口

文档首页位于 `docs/index.md`，站点导航由 `mkdocs.yml` 统一管理。
