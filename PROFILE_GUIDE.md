# GitHub Profile 美化说明

这个 GitHub 主页使用了以下流行的开源项目来实现美化效果：

## 🎨 使用的开源项目

### 1. [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
- **功能**: 动态显示 GitHub 统计信息和常用语言
- **使用位置**: "📊 GitHub Statistics" 部分
- **特点**: 支持多种主题，实时更新，可自定义

### 2. [GitHub Readme Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats)
- **功能**: 显示连续贡献天数统计
- **使用位置**: "📊 GitHub Statistics" 部分
- **特点**: 激励持续贡献，显示最长连续记录

### 3. [GitHub Readme Activity Graph](https://github.com/ashutosh00710/github-readme-activity-graph)
- **功能**: 显示贡献活动图表
- **使用位置**: "📊 GitHub Statistics" 部分
- **特点**: 可视化展示贡献趋势

### 4. [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy)
- **功能**: 根据 GitHub 活动显示奖杯成就
- **使用位置**: "🏆 GitHub Trophies" 部分
- **特点**: 游戏化展示，提供多种奖杯类型

### 5. [Readme Typing SVG](https://github.com/DenverCoder1/readme-typing-svg)
- **功能**: 创建动态打字效果的 SVG
- **使用位置**: 顶部标题
- **特点**: 吸引眼球，可自定义文字和动画效果

### 6. [Shields.io](https://shields.io/)
- **功能**: 生成各种徽章 (badges)
- **使用位置**: "🛠️ Tech Stack" 和 "📫 Connect with Me" 部分
- **特点**: 大量预设徽章，支持自定义

### 7. [GitHub Readme Quotes](https://github.com/PiyushSuthar/github-readme-quotes)
- **功能**: 每日随机显示编程名言
- **使用位置**: "💭 Quote of the Day" 部分
- **特点**: 每次访问显示不同的励志名言

### 8. [Profile Counter](https://github.com/antonkomarev/github-profile-views-counter)
- **功能**: 统计主页访问次数
- **使用位置**: "👀 Profile Views" 部分
- **特点**: 简单直观的访问计数器

### 9. [Snake Game Animation](https://github.com/Platane/snk)
- **功能**: 将 GitHub 贡献图转换为贪吃蛇动画
- **使用位置**: "📈 Contribution Graph" 部分
- **特点**: 趣味性展示，通过 GitHub Actions 自动生成
- **配置**: 已添加 `.github/workflows/snake.yml` 工作流

## 🎨 主题配色

所有组件统一使用 **Tokyo Night** 主题，保持视觉一致性：
- 深色背景
- 紫色/蓝色主色调
- 现代简约风格

## 📝 自定义说明

### 修改个人信息
在 `README.md` 文件中的 TypeScript 代码块中更新：
- `location`: 你的位置
- `code`: 你使用的编程语言
- `technologies`: 你的技术栈
- `currentFocus`: 当前关注点

### 修改主题
将所有 `theme=tokyonight` 替换为其他主题：
- `radical`
- `merko`
- `gruvbox`
- `dark`
- `dracula`
等等...

### 添加更多功能
可以考虑添加：
- [GitHub Profile 3D Contrib](https://github.com/yoshi389111/github-profile-3d-contrib) - 3D 贡献图
- [WakaTime Stats](https://github.com/anmol098/waka-readme-stats) - 编程时间统计
- [Spotify Playing](https://github.com/novatorem/novatorem) - 正在播放的音乐

## 🚀 自动更新

贪吃蛇动画通过 GitHub Actions 自动更新：
- 每天 UTC 00:00 自动运行
- 也可以手动触发
- 生成的 SVG 保存在 `output` 分支

## 📚 更多资源

- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
- [GitHub Profile README Generator](https://github.com/rahuldkjain/github-profile-readme-generator)
