# 产品设计方法论AI生成器

🚀 从想法到MVP，AI驱动的产品设计全流程工具

## 项目简介

这是一个基于AI的产品设计方法论生成器，帮助产品经理和创业者系统化地将产品想法转化为可执行的MVP原型。通过6个步骤，结合JTBD、用户故事地图、卡诺模型等经典产品方法论，快速完成产品设计全流程。

## 在线演示

🌐 访问地址：[https://yourusername.github.io/product-design-methodology-generator](https://yourusername.github.io/product-design-methodology-generator)

## 功能特色

### 6步式产品设计流程

1. **💡 产品想法优化**
   - AI分析你的产品概念
   - 识别目标用户、核心问题、独特价值
   - 提供商业模式建议

2. **🎯 JTBD分析**
   - 生成Jobs to be Done陈述句
   - 四力分析（推力、拉力、焦虑、惯性）
   - 理解用户真实需求

3. **🗺️ 用户故事地图**
   - 可视化用户旅程
   - 识别核心功能列表
   - 功能优先级排序

4. **💎 卡诺模型分析**
   - 功能分类（必备、期望、魅力）
   - 科学评估功能价值
   - MVP范围建议

5. **📄 产品设计文档**
   - 生成完整PRD文档
   - 包含需求分析、功能规格
   - 支持下载和复制

6. **🏗️ MVP原型代码**
   - 技术栈建议
   - 生成可运行的HTML原型
   - 包含核心功能实现

## 技术栈

- **前端**: 纯HTML + CSS + JavaScript
- **AI**: Claude API (Anthropic)
- **部署**: GitHub Pages
- **特点**: 无需构建工具，开箱即用

## 使用方法

### 1. 在线使用

直接访问在线演示地址，按照页面提示操作即可。

### 2. 本地运行

```bash
# 克隆仓库
git clone https://github.com/yourusername/product-design-methodology-generator.git

# 进入目录
cd product-design-methodology-generator

# 使用任意HTTP服务器运行
# 方法1: Python
python -m http.server 8000

# 方法2: Node.js
npx http-server

# 访问 http://localhost:8000
```

### 3. 配置API Key

本工具需要使用Claude API。使用前请确保：

1. 注册Anthropic账号并获取API Key
2. 在代码中配置你的API Key（位于`callClaudeAPI`函数）
3. 或者修改为使用环境变量管理API Key

**注意**: 请勿将API Key提交到公开仓库，建议使用环境变量或配置文件管理。

## 核心特性

✨ **AI驱动**: 基于Claude AI的强大分析能力  
📱 **响应式设计**: 完美支持移动端和桌面端  
🎨 **现代UI**: 渐变色背景、流畅动画、卡片式布局  
💾 **数据持久化**: 自动保存各步骤数据  
✏️ **可编辑内容**: AI生成的内容都可以手动调整  
📥 **导出功能**: 支持下载文档和代码  
📋 **一键复制**: 快速复制到剪贴板  

## 设计理念

本工具整合了多种经典产品方法论：

- **JTBD (Jobs to be Done)**: 理解用户真实需求
- **用户故事地图 (User Story Mapping)**: 可视化产品功能
- **卡诺模型 (Kano Model)**: 科学评估功能优先级
- **精益创业 (Lean Startup)**: 快速验证MVP

## 项目结构

```
product-design-methodology-generator/
├── index.html              # 主页面（完整的单文件应用）
├── README.md               # 项目说明
├── CHANGELOG.md           # 更新日志
└── JSON解析错误修复说明.md  # 技术文档
```

## 开发计划

- [ ] 支持多种AI模型选择
- [ ] 添加用户账号系统，保存历史项目
- [ ] 导出更多格式（PDF、Word）
- [ ] 添加团队协作功能
- [ ] 多语言支持（英文、日文等）
- [ ] 提供更多产品模板

## 常见问题

### Q: 需要API Key吗？
A: 是的，需要Anthropic的Claude API Key。请访问 [Anthropic官网](https://www.anthropic.com/) 获取。

### Q: 数据会保存在哪里？
A: 当前版本数据仅保存在浏览器内存中，刷新页面会丢失。建议及时下载生成的文档。

### Q: 是否支持离线使用？
A: 界面可以离线访问，但AI生成功能需要网络连接调用API。

### Q: 生成的内容可以商用吗？
A: 可以。生成的内容归你所有，可用于任何商业目的。

## 贡献指南

欢迎提交Issue和Pull Request！

1. Fork本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的修改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个Pull Request

## 许可证

本项目采用 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

## 致谢

- [Anthropic Claude](https://www.anthropic.com/) - 提供强大的AI能力
- [GitHub Pages](https://pages.github.com/) - 免费的静态网站托管

## 作者

👨‍💻 Created by [Your Name]

## 版本历史

查看 [CHANGELOG.md](CHANGELOG.md) 了解详细更新历史。

---

**当前版本**: 1.0  
**更新日期**: 2025-12-04

如有问题或建议，欢迎提交 [Issue](https://github.com/yourusername/product-design-methodology-generator/issues)
