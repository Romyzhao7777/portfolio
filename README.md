# 个人作品集网站

这是一个现代化的个人作品集网站，专为申请UI/UX设计相关的暑期实习而设计。

## 功能特点

- 🎨 **现代化设计** - 采用渐变色彩和流畅动画，注重视觉美感
- 📱 **完全响应式** - 适配桌面、平板和移动设备
- ⚡ **流畅交互** - 平滑滚动、动画效果和交互反馈
- 🎯 **突出重点** - 展示个人技能、项目经验和专业优势

## 网站结构

- **首页 (Hero)** - 个人介绍和主要信息
- **关于我** - 教育背景、专业优势和设计理念
- **技能** - 设计工具、编程语言和数据分析能力
- **项目** - 精选的GitHub项目展示
- **联系** - 联系方式和社会媒体链接

## 使用方法

1. 直接在浏览器中打开 `index.html` 文件即可查看网站
2. 或者使用本地服务器运行（推荐）：
   ```bash
   # 使用Python
   python -m http.server 8000
   
   # 使用Node.js (需要安装http-server)
   npx http-server
   ```
3. 在浏览器中访问 `http://localhost:8000`

## 自定义内容

### 更新个人信息
编辑 `index.html` 文件中的以下部分：
- Hero部分的姓名和介绍
- About部分的教育背景和优势
- Contact部分的邮箱地址

### 更新项目
在 `index.html` 的 Projects 部分添加或修改项目卡片：
- 项目标题和描述
- GitHub链接
- 项目标签

### 修改颜色主题
在 `styles.css` 文件的 `:root` 部分修改CSS变量：
```css
--primary-color: #6366f1;
--secondary-color: #8b5cf6;
--accent-color: #ec4899;
```

## 技术栈

- HTML5
- CSS3 (使用CSS变量、Grid、Flexbox)
- JavaScript (原生JS，无依赖)
- Google Fonts (Inter & Playfair Display)

## 浏览器支持

- Chrome (最新版本)
- Firefox (最新版本)
- Safari (最新版本)
- Edge (最新版本)

## 注意事项

- 请确保更新联系部分的邮箱地址
- 可以根据需要添加更多项目
- 建议添加实际的项目截图或演示链接
- 可以考虑添加作品集PDF下载链接

## 未来改进建议

- 添加深色模式切换
- 集成联系表单
- 添加项目详情页面
- 集成Google Analytics
- 添加多语言支持
