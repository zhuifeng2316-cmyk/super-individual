# AI 设计工具全解

## 核心概念

设计不再是设计师的专利。AI 设计工具让非设计背景的超级个体也能产出专业级视觉内容。

## 主流工具对比

| 工具 | 用途 | 强项 | 价格 | 学习曲线 |
|------|------|------|------|---------|
| Midjourney | AI 绘图 | 艺术风格、创意视觉 | $10/月起 | 中 |
| DALL-E 3 | AI 绘图 | 文字理解精准、细节好 | ChatGPT Plus | 低 |
| Stable Diffusion | AI 绘图 | 开源免费、可本地运行 | 免费/自部署 | 高 |
| Canva | 平面设计 | 模板丰富、操作简单 | 免费/Pro | 极低 |
| Figma | UI设计 | 协作、组件系统 | 免费/付费 | 中 |
| v0.dev | UI生成 | 文字生成前端组件 | 免费/付费 | 低 |
| Remove.bg | 抠图 | 一键去背景 | 免费/付费 | 极低 |
| Looka | Logo设计 | AI 生成品牌视觉 | 一次性付费 | 极低 |

## 实操步骤

### Step 1：建立设计 Prompt 词汇库

**Midjourney 高效 Prompt 结构**：
```
[主体] + [风格] + [色调] + [构图] + [质量词]

示例：
"A solo entrepreneur working at a minimalist desk, 
flat illustration style, blue and orange palette, 
wide angle, --ar 16:9 --v 6 --q 2"
```

**常用风格关键词**：
- 扁平插画：`flat illustration, minimal`
- 3D 风格：`3D render, isometric, soft lighting`
- 照片级：`photorealistic, 8k, detailed`
- 赛博朋克：`cyberpunk, neon, futuristic`
- 手绘风：`hand-drawn, watercolor, sketch`

### Step 2：超级个体设计工作流

```
品牌视觉（Looka/Midjourney 一次生成）
  ├── Logo + 配色方案
  ├── 社交媒体模板（Canva 批量生成）
  └── 网站视觉（v0.dev + Midjourney 配图）

内容配图（AI 流水线）
  ├── 文章封面：Midjourney 生成 → Canva 加文字
  ├── 社交图片：Canva 模板 → 换文案
  └── 视频封面：Midjourney → 剪映加标题

产品设计（Figma + AI）
  ├── UI 组件：v0.dev 生成
  ├── 交互原型：Figma 制作
  └── 开发交付：Cursor 实现
```

### Step 3：建立品牌设计系统

在 [Vigma](https://vigma.app) 统一管理：
- 🎨 配色方案（主色/辅色/中性色）
- 🔤 字体规范（标题/正文/强调）
- 📐 间距系统（4px/8px 基准网格）
- 🖼️ 图片风格指南（AI Prompt 模板）

## 注意事项

- ⚠️ AI 生成图片注意版权——商用需确认授权
- ⚠️ Midjourney 生成的图片中文字可能乱码，后期用 Canva 加文字
- ⚠️ 保持品牌一致性比追求创意更重要
- ⚠️ 不要过度设计——超级个体追求效率，不是艺术展

## 参考链接

- Midjourney Prompt 词典
- [Vigma](https://vigma.app) — 品牌设计系统管理
- Canva 设计学院

---
*最后更新：2026-04-15*
