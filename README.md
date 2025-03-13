# 软件顾问经理个人网站

这是一个专业的软件顾问经理个人展示网站，用于展示专业背景、服务内容和联系方式。

## 网站特点

- 响应式设计，适配各种设备屏幕
- 现代化UI界面，专业简洁
- 包含个人介绍、服务内容、专业经验、客户评价和联系方式等部分
- 交互式导航和平滑滚动效果
- 客户评价轮播展示
- 联系表单功能

## 技术栈

- HTML5
- CSS3 (使用现代CSS变量和Flexbox/Grid布局)
- JavaScript (原生JS，无依赖)
- Font Awesome 图标库
- Google Fonts (思源黑体)

## 文件结构

```
├── index.html          # 主HTML文件
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── main.js         # JavaScript交互脚本
└── img/                # 图片资源文件夹
```

## 使用说明

1. 克隆或下载此仓库到本地
2. 使用浏览器打开`index.html`文件即可查看网站
3. 根据需要修改内容:
   - 在`index.html`中修改个人信息、服务内容等文本
   - 在`css/style.css`中调整样式和颜色
   - 在`js/main.js`中自定义交互行为

## 自定义

### 更换图片

1. 将您的个人照片放入`img`文件夹
2. 在`index.html`中更新图片路径
3. 可以替换背景图片，修改`css/style.css`中的`.hero`背景图片路径

### 修改颜色主题

在`css/style.css`文件开头的`:root`部分修改颜色变量:

```css
:root {
    --primary-color: #2563eb;  /* 主色调 */
    --secondary-color: #1e40af;  /* 次要色调 */
    /* 其他颜色变量... */
}
```

### 添加新的服务项目

在`index.html`的服务部分添加新的服务卡片:

```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-[图标名称]"></i>
    </div>
    <h3>服务名称</h3>
    <p>服务描述...</p>
</div>
```

## 联系表单配置

当前联系表单仅作为演示，实际使用时需要配置后端处理逻辑:

1. 创建处理表单提交的后端API
2. 在`js/main.js`中取消注释AJAX请求部分，并更新API端点

## 许可

此项目仅供个人使用，未经授权不得用于商业目的。

## 更新日志

- 2023-03-13: 网站初始版本发布，优化了移动端显示效果 