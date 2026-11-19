# ldm-skill-demo

Claude 自定义技能库，挂载仓库后可通过命令直接调用。

## 目录规范

- 技能文件统一放在 `.claude/skills/` 目录。
- 每个文件为一个 Markdown 技能，顶部用 `name`、`description`、`trigger` 声明。

## 技能列表

### 开发与需求
- `/grill-me`：深入盘问、挖掘需求细节，把模糊需求拆清楚。
- `/tdd`：测试驱动开发，先写测试再实现代码。
- `/to-spec`：把需求转换成清晰技术规格文档。
- `/refactor`：安全重构代码，不改动原有行为。
- `/review`：代码评审，找出漏洞、性能、规范、安全问题。

### 工作协作
- `/task-breakdown`：把复杂目标拆成可执行、可验收的小任务。
- `/meeting-notes`：把会议内容整理成结论、待办、负责人和截止时间。
- `/email-summary`：把长邮件提炼成背景、诉求、关键时间和下一步。
- `/checklist`：按清单逐项核对，标出完成、缺失和待确认项。

### 生活实用
- `/compare-products`：对比同类商品的价格、规格、优缺点和适用场景。
- `/travel-checklist`：生成出行证件、衣物、用品和应急事项清单。
