# 组件台账模板

## 文档目的

本篇提供一个基础台账模板，用于记录团队引入和维护的第三方开源组件信息。

组件台账的核心作用是让依赖来源、版本、License 和使用范围可追溯。

## 推荐字段

建议至少记录以下字段：

| 字段 | 说明 |
| --- | --- |
| 组件名称 | 第三方组件或库的名称 |
| 版本 | 当前使用版本 |
| 来源地址 | 官方仓库、官网或官方包地址 |
| License | 组件采用的 License 类型 |
| 使用模块 | 在哪个系统、服务或模块中使用 |
| 使用目的 | 为什么引入该组件 |
| 引入时间 | 首次引入时间 |
| 责任人 | 当前负责维护的人 |
| 修改情况 | 是否修改过第三方源码 |
| 风险等级 | 低、中、高 |
| 备注 | 其他需要说明的信息 |

## Markdown 模板

如果想先用最简单的方式维护，可以直接在仓库中记录成表格：

| 组件名称 | 版本 | 来源地址 | License | 使用模块 | 使用目的 | 引入时间 | 责任人 | 修改情况 | 风险等级 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| example-lib | 1.2.3 | https://example.com/repo | MIT | user-service | JSON 处理 | 2026-04-26 | swartz | 否 | 低 | - |
| another-lib | 4.5.6 | https://example.com/repo2 | Apache-2.0 | web-app | HTTP 客户端 | 2026-04-26 | swartz | 否 | 低 | 需关注 NOTICE |

## CSV 字段模板

如果后续要导入到表格系统或资产系统，可以使用如下字段顺序：

```text
component_name,version,source_url,license,usage_module,usage_purpose,introduced_at,owner,modified,risk_level,notes
```

## 最低维护要求

如果暂时做不到完整治理，至少也建议保证下面几项始终准确：

1. 组件名称
2. 版本
3. 来源地址
4. License

## 维护建议

- 新组件引入时同步登记
- 组件升级时同步更新版本和备注
- 修改过第三方源码时同步更新“修改情况”
- 高风险 License 组件单独标记

## 关联文档

- [开源组件引入检查清单](component-intake-checklist.md)
- [发布前合规检查清单](release-compliance-checklist.md)
