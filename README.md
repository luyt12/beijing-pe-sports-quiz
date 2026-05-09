# 🏃 北京市初中体育与健康知识笔试刷题系统

一个简洁的体育知识在线练习系统，适配北京市初中体育笔试。

**在线访问**：https://luyt12.github.io/beijing-pe-sports-quiz

## ✨ 功能特点

- 📝 **逐题作答** - 一次只显示一道题，专注学习
- ✅ **即时判分** - 选择后立即显示对错
- 💡 **趣味解析** - 每道题都有详细解析和易错提醒
- 🔄 **错题复盘** - 答错会高亮正确答案
- 📱 **适配手机** - 支持移动端随时刷题

## 🚀 快速使用

### 方法一：直接打开（推荐）

直接在浏览器中打开 `index.html` 文件即可使用。

### 方法二：部署到 GitHub Pages

本仓库已启用 GitHub Pages，可直接访问：
https://luyt12.github.io/beijing-pe-sports-quiz

### 方法三：本地运行

```bash
# 克隆仓库
git clone https://github.com/luyt12/beijing-pe-sports-quiz.git

# 进入目录
cd beijing-pe-sports-quiz

# 用浏览器打开 index.html
```

## 📖 题库说明

题库位于 `index.html` 文件底部的 JavaScript 代码中，格式如下：

```javascript
const questions = [
    {
        title: "题目内容",
        options: ["A. 选项1", "B. 选项2", "C. 选项3", "D. 选项4"],
        answer: "B",
        analysis: "✅ 答对啦！<br>👉 解析内容<br>❌ 易错坑：..."
    }
];
```

### 添加新题目

在 `questions` 数组中添加新对象即可：

```javascript
const questions = [
    // 已有题目...
    {
        title: "新题目内容",
        options: ["A. 选项1", "B. 选项2", "C. 选项3", "D. 选项4"],
        answer: "C",
        analysis: "解析内容<br>👉 提示<br>❌ 易错提醒"
    }
    // 注意：最后一个题目后面不要加逗号
];
```

**注意**：
- 所有标点符号必须使用英文标点
- 引号、逗号、大括号都不能用中文的

## 📁 项目结构

```
beijing-pe-sports-quiz/
├── index.html   # 主页面（包含题库和所有代码）
└── README.md    # 说明文档
```

## 🔧 自定义

如果想创建自己的题库，修改 `index.html` 中的 `questions` 数组即可。可以修改标题、题目数量、样式等。

## 📝 题目列表

当前包含以下题目：

1. 中长跑运动中正确的呼吸方法
2. 立定跳远落地时的正确动作
3. 运动后大量出汗最适合补充的饮品

## 📄 许可证

MIT License - 随意使用和修改

---

Made with ❤️ for Beijing PE Exam Students
