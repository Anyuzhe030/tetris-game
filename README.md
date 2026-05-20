# 🎮 俄罗斯方块 - 网页版

一个用 HTML5 + JavaScript 写的俄罗斯方块游戏，无需安装任何软件，直接在浏览器里就能玩！

## 🎯 游戏地址

**https://你的用户名.github.io/tetris-game/**

（把「你的用户名」替换成你的 GitHub 用户名，部署步骤见下方）

## 🎮 操作说明

| 按键 | 功能 |
|------|------|
| ← → | 左右移动 |
| ↓ | 加速下落 |
| 空格 | 方块变形 |
| P | 暂停 / 继续 |

## 📱 手机支持

触屏用户可以点击屏幕下方的按钮进行操作。

## 🛠️ 技术栈

- HTML5 Canvas（画布渲染）
- 纯 JavaScript（无任何依赖库）
- CSS3（样式和动画）

## 📁 文件结构

```
tetris-game/
├── index.html      ← 游戏主文件（包含 HTML + CSS + JS）
├── pause.jpg       ← 暂停弹窗图片（必须！不放则显示占位文字）
├── gameover.jpg    ← 结束弹窗图片（必须！不放则显示占位文字）
└── README.md       ← 你正在看的文件
```

## 🎨 自定义颜色

打开 `index.html`，找到 JavaScript 里的颜色定义，可以随意修改：

```javascript
const COLOR_BLOCK   = "#FFBBCF";  // 方块填充色（粉色）
const COLOR_BORDER  = "#D393FF";  // 边界颜色（紫色）
const COLOR_EMPTY   = "#0a0a1a";  // 空格子背景（深蓝黑）
```

把颜色值改成你喜欢的颜色即可。

## 🚀 部署到 GitHub Pages

### 第一步：创建仓库
1. 打开 https://github.com ，登录账号
2. 点击右上角 **"+"** → **New repository**
3. 仓库名称填 `tetris-game`，选择 **Public**
4. 点击 **Create repository**

### 第二步：上传文件
把 `D:\28245\tetris-web\` 文件夹里的 **全部 4 个文件**（index.html、pause.jpg、gameover.jpg、README.md）全部拖到仓库上传页面，上传后点击 **Commit changes**

### 第三步：开启 GitHub Pages
1. 进入仓库 → **Settings** → 左侧 **Pages**
2. **Source**：选择 `Deploy from a branch`
3. **Branch**：选择 `main`，文件夹选 `/ (root)`
4. 点击 **Save**

### 第四步：获取链接
等待 1~2 分钟，刷新 Settings → Pages 页面，看到绿色提示：

```
Your site is live at https://你的用户名.github.io/tetris-game/
```

把这个链接分享给朋友即可！**他们不需要安装任何东西，点开就能玩！**

