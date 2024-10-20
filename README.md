# Boblog - 轻量级免部署文档系统

Boblog 是一个简单、轻量级的文档系统，无需服务器部署，直接在浏览器中运行。它支持 Markdown 格式的文档，提供了简洁的界面和实用的功能。

## 特性

- 轻量级：无需服务器，直接在浏览器中运行
- Markdown 支持：使用 Markdown 格式编写文档
- 响应式设计：适配桌面和移动设备
- 主题切换：支持亮色和暗色主题
- 搜索功能：快速搜索文档内容
- 简洁界面：基于 MDUI 框架，提供现代化的 Material Design 界面

## 快速开始

1. 克隆或下载本项目到本地。
2. 在项目根目录创建 `sidebar.md` 文件，用于定义侧边栏菜单结构。
3. 创建 Markdown 文档文件，放置在项目根目录或子目录中。
4. 使用浏览器打开 `index.html` 文件即可浏览文档。

## 配置说明

### 侧边栏菜单配置

在 `sidebar.md` 文件中使用以下格式定义菜单项：

```
[图标][菜单名称][文档路径]
```

例如：

```
[home][首页][README.md]
[description][介绍][intro.md]
[code][示例][examples/example1.md]
```

### Markdown 文档

- 使用标准的 Markdown 语法编写文档。
- ~~使用 `##` 和 `###` 来定义二级和三级标题，这些标题将自动生成目录。~~（未来展望）

## 主要功能

1. **主题切换**：点击右上角的主题图标可以在亮色和暗色主题之间切换。

2. ~~**目录导航**：~~

3. **搜索功能**：
   - 点击右上角的搜索图标打开搜索框。
   - 输入关键词可搜索所有文档内容。
   - 搜索结果显示文档标题和匹配内容片段。

4. **响应式设计**：
   - 自适应不同屏幕尺寸，提供良好的移动端体验。

## 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)
- [MDUI](https://www.mdui.org/): Material Design 用户界面框架
- [Marked](https://marked.js.org/): Markdown 解析器

## 自定义

- 修改 `<style>` 标签中的 CSS 可以自定义界面样式。
- 在 `<script>` 标签中可以调整或扩展 JavaScript 功能。

## 注意事项

- 本系统基于浏览器的文件系统访问，某些浏览器可能会有安全限制。建议使用现代浏览器并在本地服务器环境下运行。
- 为了最佳体验，建议使用最新版本的 Chrome、Firefox 或 Edge 浏览器。

## 贡献

欢迎提交 Issues 或 Pull Requests 来帮助改进这个项目。

## 许可证

本项目采用 MIT 许可证。详情请见 [LICENSE](LICENSE) 文件。
