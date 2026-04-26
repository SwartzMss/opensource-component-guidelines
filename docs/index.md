# 开源组件治理文档

这个站点用于沉淀团队在使用开源组件时需要遵循的基本规范、License 知识和合规处理方法。

它不是某一个组件的使用说明，而是一套面向工程治理的文档体系，帮助团队在组件选型、接入、发布和维护过程中降低法律、合规和工程风险。

## 适用对象

- 研发工程师
- 架构师和技术负责人
- 安全、法务、合规相关角色
- 负责开源治理或软件资产治理的团队

## 内容结构

### 1. 使用规范

这一部分回答“开源组件该怎么引入、怎么管、怎么发布”。

- [开源组件使用规范](component-usage-guidelines.md)
- [开源组件引入检查清单](component-intake-checklist.md)
- [依赖引入申请模板](component-intake-request-template.md)
- [发布前合规检查清单](release-compliance-checklist.md)
- [组件台账模板](component-inventory-template.md)

### 2. License

这一部分回答“不同 License 到底有什么差异，商用、修改、分发、闭源边界怎么看”。

- [常见 License 介绍](common-licenses.md)
- [常见 License 对比表](license-comparison-matrix.md)
- [License 权限与义务](license-rights-and-obligations.md)

### 3. 合规实践

这一部分回答“规则如何在实际项目里落地”。

- [开源合规流程](compliance-process.md)
- [典型场景案例](typical-scenarios.md)
- [第三方声明模板](third-party-notices-template.md)

## 建议阅读顺序

如果第一次接触这个主题，建议按下面顺序阅读：

1. 先看 [开源组件使用规范](component-usage-guidelines.md)
2. 再看 [常见 License 介绍](common-licenses.md)
3. 然后看 [License 权限与义务](license-rights-and-obligations.md)
4. 最后看 [开源合规流程](compliance-process.md)

## 当前边界

本项目用于提供工程治理层面的通用指导，不替代正式法律意见。

对于以下场景，仍然建议结合正式法务或合规流程单独评估：

- 对外商业分发软件
- 使用强 Copyleft License 组件
- 修改并再分发第三方开源代码
- 将开源代码嵌入闭源产品
- 涉及专利授权或专利风险的组件

## 后续可以继续增强的方向

- 增加真实示例台账文件
- 增加真实第三方声明示例
- 增加 SBOM 相关实践
- 增加自动化扫描工具接入建议
