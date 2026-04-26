# 第三方声明模板

## 文档目的

本篇提供一个基础模板，便于团队在对外发布软件时整理第三方开源组件声明。

不同产品和不同 License 的具体要求可能不同，这个模板应根据实际依赖情况调整。

## 适用场景

适用于以下常见场景：

- 客户端软件发布
- 安装包交付
- 镜像、SDK、插件包发布
- 其他包含第三方开源组件的对外交付物

## 基础模板

可以在发布物中附带类似如下内容：

```text
Third-Party Notices

This product includes third-party open source software components.
The copyright ownership of these components belongs to their respective
authors or copyright holders.

The following open source components are included in this product:

1. Component Name: <component-name>
   Version: <version>
   Source: <repository-or-homepage>
   License: <license-name>
   Copyright: <copyright-notice-if-applicable>

2. Component Name: <component-name>
   Version: <version>
   Source: <repository-or-homepage>
   License: <license-name>
   Copyright: <copyright-notice-if-applicable>

The full license texts for the above components are provided in the
corresponding license appendix or license files distributed with this product.
```

## 中文说明模板

如果交付物需要中文说明，也可以使用类似表达：

```text
第三方开源组件声明

本产品包含若干第三方开源软件组件，其著作权归原作者或原权利人所有。

本产品中使用的第三方开源组件包括但不限于：

1. 组件名称：<component-name>
   版本：<version>
   来源：<repository-or-homepage>
   License：<license-name>
   版权声明：<copyright-notice-if-applicable>

2. 组件名称：<component-name>
   版本：<version>
   来源：<repository-or-homepage>
   License：<license-name>
   版权声明：<copyright-notice-if-applicable>

相关 License 正文及附加声明，见本产品随附的第三方 License 文件或声明附件。
```

## 最低字段建议

即使团队目前流程不完善，至少也建议为每个第三方组件记录：

- 组件名称
- 版本
- 来源地址
- License 类型

如果条件允许，再补充：

- 版权声明
- 是否有修改
- License 正文存放位置
- NOTICE 文件内容

## 配套文件建议

对外发布时，建议把以下材料一起准备：

- 第三方组件清单
- 各组件 License 正文
- 必要的版权声明
- 如适用，NOTICE 文件或等效声明

## 常见问题

### 只写组件名字够不够

通常不够。至少还应包含版本、来源和 License 信息，否则后续难以审计和核对。

### 只在仓库里保留 License 行不行

未必够。如果产品存在独立分发物，通常应确保声明和 License 文本随发布物一起提供。

### 内部系统要不要准备这个模板

如果纯内部使用且不对外交付，外部分发义务通常较弱，但保留台账和基础记录仍然有价值。

## 关联文档

- [开源合规流程](compliance-process.md)
- [开源组件引入检查清单](component-intake-checklist.md)
