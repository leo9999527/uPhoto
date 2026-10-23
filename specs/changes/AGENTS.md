# 规格变更规范

- 每个独立功能或行为变化建立一个 `changes/<change-id>/` 目录。
- 变更 ID 使用简短 kebab-case，例如 `photographer-onboarding`、`text-messaging`、`booking-deposit`。
- 依模板维护提案、规格、任务；涉及跨模块/资金/权限/存储方案时补设计说明。
- 实现前确定范围和验收要求；关键问题未决时标出阻塞范围，不自行猜测。
- 每个任务可追溯到一个或多个 Requirement ID；每个要求至少对应一个验收场景。
- 完成并验证后更新功能基线，再将变更移至 `archive/`，不要直接删除历史规格。
