# Dark Snowy Night Theme (极简清透雪夜主题)

专为 **Antigravity** 与 **BetterGravity** 打造的极简清透毛玻璃雪夜壁纸主题。

## ✨ 特性亮点 (Features)

- ❄️ **沉浸式雪夜壁纸**：挂载高清雪夜街景壁纸，全透明顶栏与侧边栏无缝融入桌面与壁纸。
- 🔮 **通透毛玻璃界面**：输入框、右侧面板、模型选择、Turbo 权限与上下文弹出层均升级为通透高级毛玻璃（Backdrop Filter Blur），去除突兀白框与厚重黑块。
- 🎯 **精致交互与智能选中态**：
  - **未选中态**：文字与图标保持清晰纯白（`#f8fafc`），底色全透明无多余色块遮挡；
  - **动态选中高亮**：无论是开启新对话（`+ New Conversation`）还是历史对话项，光标与选择停留在哪，即自动呈现非常浅的白色半透明毛玻璃底板（`rgba(255, 255, 255, 0.82)`），文字与图标自动反转为高对比度深黑字（`#0f172a`），优雅而醒目。
- 🛑 **核心组件与细节修复**：
  - 精确保护并高亮输入框右下角鲜明的红色暂停/取消方块（Cancel Ctrl+D）；
  - 侧边栏对话行悬浮操作（归档、固定、更多三点）彻底消除 Tailwind 默认注入的黑色渐变遮罩；
  - 仅代码、函数名、行内参数代码使用清透冰蓝（`#7dd3fc`）高亮，普通中文正文与说明保持柔和纯白，阅读更舒适。

---

## 📦 目录结构 (Structure)

```text
snowy-theme/
├── theme.css        # 主题核心样式表（含 BetterGravity 主题元信息）
├── background.png   # 2K 高清雪夜街景壁纸
└── README.md        # 主题介绍与安装说明
```

---

## 🚀 安装与使用 (Installation)

### 配合 BetterGravity 使用
1. 确保已安装并配置好 **BetterGravity** 框架；
2. 将本主题文件夹 `snowy-theme` 复制放置于 BetterGravity 的主题目录下：
   - **Windows 路径**：`%APPDATA%\BetterGravity\themes\snowy-theme`
   - （即 `C:\Users\<你的用户名>\AppData\Roaming\BetterGravity\themes\snowy-theme`）
3. 重启或在 BetterGravity / Antigravity 设置中勾选激活 **Dark Snowy Night Theme** 即可立即生效。

---

## 📝 主题元数据 (Metadata)

- **主题名称**：Dark Snowy Night Theme
- **作者**：时尘
- **当前版本**：v3.6.0
- **适用平台**：Antigravity (with BetterGravity)
