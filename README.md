# 🗂️ 展示板管理器 | Dashboard Manager

一个功能强大的单文件 HTML 展示板应用，无需任何依赖，下载即用。

A powerful single-file HTML dashboard application with zero dependencies — download and use instantly.

---

## ✨ 功能 | Features

### 📦 内容类型 | Content Types
- 📝 **文本** — 点击即编辑，支持 Markdown 渲染、字体/字号自定义
- 🖼️ **图片** — 拖拽导入，base64 持久化存储
- 📄 **PDF** — 拖拽导入，内嵌预览，base64 持久化
- 🌐 **网页嵌入** — iframe 嵌入任意 URL
- 📊 **数据表格** — 导入 CSV，自动渲染为可排序表格

### 🖱️ 交互 | Interaction
- **自由拖拽** 方块位置，8 方向缩放
- **对齐吸附** — 拖拽时自动吸附邻近方块边缘
- **折叠/展开**、**锁定/解锁**、**复制方块**
- **Shift 多选** — 批量移动、对齐、删除，方向键微调
- **置于顶层/底层** — 图层管理

### 📑 多展示板 | Multi-Dashboard
- 标签页管理，独立内容空间
- 各展示板可独立配置颜色、重叠模式

### 🎨 样式 | Styling
- 🎨 方块/展示板自定义颜色
- 🔲 圆角滑块（0–30px）
- 🌙 暗色模式（Ctrl+D）
- 📐 网格吸附模式

### 🔗 连接与分组 | Connections & Groups
- **SVG 连接线** — 右键创建，拖拽跟随
- **分组包围框** — 选中方块一键创建分组

### 🏷️ 标签与搜索 | Tags & Search
- 右键添加标签，顶部标签栏一键筛选
- Ctrl+F 全局搜索，实时高亮

### 🎬 演示模式 | Presentation
- 全屏幻灯片，按方块顺序翻页（← → 空格）

### 💾 存储 | Storage
- 📁 **本地文件夹** — File System Access API，数据存为 `dashboard-data.json`
- 📦 **IndexedDB** — 浏览器内置大容量存储（GB 级）
- 💿 **localStorage** — 兜底方案
- 📤📥 **JSON 导出/导入** — 备份与分享
- ↩ **撤销/重做** — Ctrl+Z / Ctrl+Y（50 步历史）

### 🗺️ 其他 | Extras
- 迷你地图 — 右下角缩略图，点击跳转
- ✏️ 涂鸦绘图 — 选颜色和笔触在画布上自由手绘
- 触屏设备支持

---

## 🚀 使用方法 | Usage

1. 下载 `dashboard.html`
2. 用浏览器打开（Chrome/Edge 推荐）
3. 点击 **💾 按钮** 选择存储文件夹（可选，数据自动保存到 `dashboard-data.json`）

### 快捷键 | Shortcuts

| 快捷键 | 功能 |
|--------|------|
| `Ctrl+N` | 新建方块 |
| `Ctrl+Shift+N` | 新建展示板 |
| `Ctrl+Z` / `Ctrl+Y` | 撤销 / 重做 |
| `Ctrl+D` | 暗色模式 |
| `Ctrl+F` | 搜索 |
| `← → ↑ ↓` | 方向键微调（Shift 加速） |
| `Delete` | 删除选中方块 |
| `Escape` | 关闭弹窗 / 取消选择 |

---

## 📋 技术栈 | Tech Stack

- 纯 HTML + CSS + JavaScript（零依赖）
- IndexedDB + File System Access API 存储
- SVG 连接线渲染
- Canvas 迷你地图与涂鸦

---

## 📄 许可 | License

MIT
