# OpenSource Component Guidelines

这个仓库用于沉淀团队在使用开源组件时需要遵循的基本规范、License 知识和合规处理方法。

它的目标不是介绍某一个具体组件，而是提供一套可复用的判断框架，帮助团队在组件选型、接入、发布和维护过程中降低法律、合规和工程风险。

## 仓库目标

- 说明什么是规范地使用开源组件
- 介绍常见开源 License 及其核心差异
- 帮助团队理解不同 License 下的权限和义务
- 提供开源组件引入、升级、发布的基础合规流程
- 为后续沉淀企业内部规则、检查清单和案例分析提供结构化载体

## 适用对象

- 研发工程师
- 架构师和技术负责人
- 安全、法务、合规相关角色
- 负责开源治理或软件资产治理的团队

## 你可以在这里看到什么

当前内容按照几个核心主题组织：

- 开源组件使用规范
- 常见 License 分类与特征
- License 的使用权限与义务
- 开源合规的基础流程

## 文档导航

- [开源组件使用规范](docs/component-usage-guidelines.md)
- [常见 License 介绍](docs/common-licenses.md)
- [常见 License 对比表](docs/license-comparison-matrix.md)
- [License 权限与义务](docs/license-rights-and-obligations.md)
- [开源合规流程](docs/compliance-process.md)
- [开源组件引入检查清单](docs/component-intake-checklist.md)
- [发布前合规检查清单](docs/release-compliance-checklist.md)
- [组件台账模板](docs/component-inventory-template.md)
- [依赖引入申请模板](docs/component-intake-request-template.md)
- [典型场景案例](docs/typical-scenarios.md)
- [第三方声明模板](docs/third-party-notices-template.md)

## 建议阅读顺序

如果是第一次接触这个主题，建议按下面顺序阅读：

1. 先看“开源组件使用规范”，理解团队为什么不能随意引入依赖
2. 再看“常见 License 介绍”，建立基础分类认知
3. 接着看“License 权限与义务”，明确商用、修改、分发和闭源等边界
4. 最后看“开源合规流程”，理解如何把规则落实到实际工作中

## 当前范围

第一版先覆盖通用原则，不替代正式法律意见，也不直接替代企业内部法务审核流程。

对于以下高风险场景，仍然应该结合内部法务或合规机制单独评估：

- 对外商业分发软件
- 使用强 Copyleft License 组件
- 修改并再分发第三方开源代码
- 将开源代码嵌入闭源产品
- 涉及专利授权或专利风险的组件

## 后续可扩展方向

- 增加 SBOM 相关实践
