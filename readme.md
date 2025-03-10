# Obsidian 数学 Callout 系统使用说明文档

## 简介
这是一个专为 Obsidian 设计的数学 Callout 样式系统（版本 v0.7），提供了一套完整的数学写作环境，包括定理、证明、问题等多种类型的样式定义。

## 功能特点

### 1. 基础样式设计
- 左侧彩色边框标识
- 悬停动画效果
- 标题与内容分离设计
- 自适应深色模式

### 2. Callout 类型

#### 数学理论类
- **Theorem（定理）**：📜 蓝色系
- **Lemma（引理）**：🌿 绿色系
- **Proposition（命题）**：📑 深紫色系

#### 逻辑体系类
- **Axiom（公理）**：⭐ 深红色系
- **Postulate（假设）**：🌐 深粉色系

#### 问题与解答类
- **Problem（问题）**：❓ 红色系
- **Exercise（练习）**：✏️ 橙色系
- **Solution（解答）**：✅ 绿色系
- **Hint（提示）**：💡 黄色系

#### 证明结构类
- **Proof（证明）**：🔍 灰色系
- **Corollary（推论）**：⇒ 紫色系
- **Conclusion（结论）**：🎯 青色系

#### 定义与技术类
- **Definition（定义）**：📖 灰色系
- **Technique（技术）**：⚙️ 青绿色系

#### 其他学术环境
- **Algorithm（算法）**：⇄ 青色系
- **Discrimination（辨析）**：⚖️ 棕色系
- **Example（示例）**：📋 紫色系
- **Property（性质）**：🏷️ 青色系
- **Methodology（方法论）**：🧮 深蓝色系
- **Observation（观察）**：🔬 绿色系
- **Paradox（悖论）**：🌀 红色系

#### 笔记工具类
- **Note（笔记）**：📔 灰色系
- **Remark（备注）**：📌 橙棕色系
- **Quote（引用）**：💭 棕色系
- **Review（复习）**：📝 蓝色系
- **Pitfall（陷阱）**：🚫 红色系

## 特殊功能

### 响应式设计
- 自动适应移动设备屏幕
- 小屏幕下优化边距和字体大小

### 打印优化
- 避免 Callout 在打印时跨页断开
- 优化打印时的显示效果

### ID 系统
- 支持隐藏 ID
- 优化内部链接显示

## 使用方法
### 1. 安装步骤
1. 下载 `math callouts v0.7.css` 文件
2. 将文件放置在 Obsidian 的 snippets 文件夹中：
   - Windows: `[你的笔记库]/.obsidian/snippets/`
   - macOS/Linux: `[你的笔记库]/.obsidian/snippets/`
3. 在 Obsidian 中启用该样式：
   - 打开设置（Settings）
   - 进入外观（Appearance）
   - 滚动到底部的 CSS 代码片段（CSS Snippets）
   - 点击刷新按钮
   - 启用 `math callouts v0.7.css`

### 2. Callout 基本语法
在 Obsidian 中使用以下语法创建 Callout：
```markdown
> [!类型] 标题（可选）
> 内容
```
例如：
```markdown
> [!theorem] 毕达哥拉斯定理
> 在直角三角形中，两直角边的平方和等于斜边的平方。
```

## 注意事项
1. 确保 CSS 片段在 Obsidian 中已启用
2. 深色模式下会自动调整显示效果
3. 移动端查看时会自动优化布局




