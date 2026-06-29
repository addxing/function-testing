# Function Testing

[![skills.sh](https://skills.sh/b/addxing/function-testing)](https://skills.sh/addxing/function-testing)

面向各类 AI 编程代理的功能测试用例生成 Skill。它可以根据 PRD、Git 提交记录或用户故事生成功能测试用例，并输出 Excel 风格测试报告。

## 安装

```bash
npx skills add addxing/function-testing
```

## 使用方式

安装后，在需要生成测试用例时，让你的 AI 代理使用这个 Skill：

```text
Use $function-testing to generate test cases for this PRD.
```

为了获得更准确的结果，建议提供以下任一种材料：

- PRD 或需求文档
- Git 提交记录或 diff
- 用户故事或功能描述

## 功能说明

这个 Skill 会指导代理：

- 分析输入材料并识别来源类型
- 提取可测试的功能点
- 设计克制且精准的测试用例，覆盖正向、异常、边界、状态切换和数据一致性等场景
- 标记 P0、P1、P2 等优先级
- 生成包含测试概述、功能点清单和测试用例的 Excel 报告结构

## 文件说明

- `SKILL.md` - Skill 指令
- `LICENSE.txt` - Apache 2.0 许可证
