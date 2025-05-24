# 游戏官网模板

这是一个现代化的游戏官网模板，采用深色主题设计，具有霓虹灯效果和流畅的动画。

## 特点

- 响应式设计，适配各种设备
- 现代简约的游戏风格
- 流畅的动画效果
- 深色主题配合霓虹色彩
- 交互式轮播图
- 动态导航栏

## 项目结构

```
├── index.html          # 主页面
├── css/
│   └── style.css      # 样式文件
├── js/
│   └── main.js        # JavaScript文件
└── images/            # 图片资源目录
```

## 使用说明

1. 克隆或下载项目
2. 在 `images` 目录中添加所需的图片资源：
   - logo.png（网站logo）
   - avatar.png（用户头像）
   - hero-image.png（主视觉图片）
3. 根据需要修改 `index.html` 中的内容
4. 可以根据需要调整 `style.css` 中的颜色变量和样式

## 自定义

### 颜色主题

在 `style.css` 文件中修改以下变量来自定义颜色主题：

```css
:root {
    --primary-color: #00f2ff;
    --secondary-color: #ff00ff;
    --background-dark: #0a0a1a;
    --background-light: #1a1a2e;
    --text-color: #ffffff;
    --text-secondary: #b3b3b3;
}
```

### 轮播图

在 `index.html` 中的 `hero-slider` 部分添加或修改轮播内容。

## 浏览器支持

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 注意事项

- 确保所有图片资源都已正确放置在 `images` 目录中
- 建议使用现代浏览器以获得最佳体验
- 移动端访问时部分动画效果可能会被简化 