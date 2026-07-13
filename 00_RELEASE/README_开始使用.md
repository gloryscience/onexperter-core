# OnExpert v3.0 完整升级包

> **版本**：v3.0 Complete Release  
> **定位**：AI Expert for Global Optical Access Networks  
> **升级主题**：工程级数字孪生、AI 原生智能运维、因果诊断、仿真护栏与受控自治  
> **关系原则**：Expert First, Product Second  
> **Knowledge 数量**：14 个正式文件，控制在 15 个以内

## 一、发布结论

本包是可直接用于 GPT Builder 的完整发布包，不是增量补丁。

它保留 OnExpert 原有的光接入网专业能力，并新增：

- 工程级设备与网络数字孪生；
- TwinGraph 因果孪生图谱；
- Temporal Twin 时间孪生；
- Self-Calibrating Twin 自校准孪生；
- Counterfactual Twin 反事实推演；
- SafeAction Sandbox 安全动作沙箱；
- 多 Agent 协同与受控自治；
- Twin-to-Knowledge 运维知识沉淀。

## 二、目录

- `01_BUILDER`：GPT Builder 顶层配置和 Instructions；
- `02_KNOWLEDGE`：14 个正式 Knowledge 文件；
- `03_STANDARDS`：中文核心能力与建模标准；
- `04_TESTS`：发布验收与测试清单；
- `manifest.json`：文件清单、SHA-256 和用途。

## 三、GPT Builder 使用方法

1. GPT 名称使用 **OnExpert GPT**。
2. 将 `01_BUILDER/A03_OnExpert_GPT_Instructions_v3.0_Compact.md` 的正文复制到 Instructions。
3. 上传 `02_KNOWLEDGE` 目录中的 14 个 Markdown 文件。
4. 不要把 README、变更记录、测试报告、HTML 演示模型作为 Knowledge 上传。
5. 按 `04_TESTS/OnExpert_v3.0_Release_Acceptance_Checklist.md` 完成验收。

## 四、核心定位

```text
OnExpert = 全球光接入网专业知识、推理、诊断、仿真与决策层
Oneasy = 可承载数据接入、资源管理、工作流与受控执行的 SaaS 平台
```

OnExpert 必须先独立解决问题；只有在场景适配、产品能力已确认时，才映射到 Oneasy。
