# 常见 License 介绍

## 文档目的

本篇用于建立对常见开源 License 的基础认知，帮助读者理解不同 License 的风格和风险差异。

## 常见分类

从治理和合规视角，可以把常见 License 粗略分成三类：

- 宽松型 License
- 弱 Copyleft License
- 强 Copyleft License

这种分类方式不是法律定义，但很适合工程实践中的快速判断。

## 宽松型 License

宽松型 License 通常允许较自由地使用、修改和分发代码，对闭源集成更友好，但通常仍要求保留原始版权声明和 License 文本。

常见代表：

- MIT
- BSD-2-Clause
- BSD-3-Clause
- Apache-2.0

### MIT

特点：

- 规则相对简单
- 允许商用
- 允许修改和再分发
- 通常允许闭源集成
- 要求保留版权声明和 License 文本

### BSD

特点：

- 与 MIT 类似，整体较宽松
- 主要义务通常是保留声明
- 某些版本包含对名称宣传使用的限制

### Apache-2.0

特点：

- 相对宽松，适合商业使用
- 允许修改和分发
- 要求保留声明
- 对专利授权和专利终止条款有更明确表达
- 对需要明确专利边界的场景通常更受重视

## 弱 Copyleft License

弱 Copyleft License 通常要求对特定范围内的修改或相关文件继续开放，但不一定会把要求扩展到整个组合软件。

常见代表：

- LGPL
- MPL-2.0

### LGPL

特点：

- 常见于库级别约束
- 在特定条件下允许与闭源软件链接使用
- 如果直接修改 LGPL 组件本身，通常需要开放相应修改部分
- 实际义务判断往往与链接方式和交付方式有关

### MPL-2.0

特点：

- 以文件级 Copyleft 著称
- 修改过的 MPL 文件通常需要继续以 MPL 方式提供
- 对整个工程的传染性通常弱于 GPL

## 强 Copyleft License

强 Copyleft License 通常对修改和再分发有更严格的开放要求，在闭源商业产品中需要特别谨慎。

常见代表：

- GPL-2.0
- GPL-3.0
- AGPL-3.0

### GPL

特点：

- 修改和分发时往往伴随更强的开源义务
- 与闭源集成的边界判断更敏感
- 不适合在未充分评估的情况下直接用于闭源分发产品

### AGPL

特点：

- 在网络服务场景下也可能触发更强的源码提供义务
- 对 SaaS 类产品尤其需要谨慎评估

## 实践中的使用建议

- 宽松型 License 一般更容易被企业接受
- 弱 Copyleft License 需要结合技术接入方式判断
- 强 Copyleft License 不应在缺少审查流程的情况下直接引入

## 注意事项

- 同一组件可能采用双 License 或多 License 模式
- 组件版本升级后 License 可能变化
- 文档、示例代码、模型、字体、图片等资源可能适用不同 License
- 组件仓库首页写的说明，不一定等同于正式 License 文件

## 延伸阅读

- [常见 License 对比表](license-comparison-matrix.md)
- [License 权限与义务](license-rights-and-obligations.md)
