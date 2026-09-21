# Iris for Codex 0.1.5

## 新增功能

- Iris 授权等待时间现在跟随 Codex 原授权请求生命周期，长时间等待后仍可在 Iris 中完成允许或拒绝。

## 修复项

- 移除 Iris 和 PermissionRequest Hook 自行设置的 10 分钟授权上限，避免 Codex Desktop 仍在等待时 Iris 提前提示授权回执过期。
