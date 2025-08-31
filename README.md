# ☀️ 光伏发电量与效益分析系统

一个专业的光伏发电量预测和经济效益分析工具，帮助用户评估太阳能投资回报。

## 🌟 功能特性

### 📊 **发电量预测**
- 24小时发电量曲线图
- 基于地理位置和系统参数的智能预测
- 实时Chart.js可视化图表

### 💰 **经济效益分析**
- 日/月/年收益计算
- 投资回报周期分析
- 碳减排量统计
- ROI投资回报率

### 🔧 **安装角度优化**
- 基于纬度的最佳角度计算
- 个性化安装建议
- 季节性调整建议

### 🎨 **现代化界面**
- 响应式设计，支持所有设备
- 科技感蓝绿色主题
- 流畅的动画和交互效果

## 🚀 在线访问

**网站地址**: [https://your-domain.vercel.app](https://your-domain.vercel.app)

## 🛠️ 技术栈

- **前端**: HTML5 + CSS3 + JavaScript (ES6+)
- **图表**: Chart.js
- **样式**: CSS Grid + Flexbox
- **图标**: Font Awesome
- **字体**: Inter (Google Fonts)
- **部署**: Vercel

## 📱 设备支持

- ✅ 桌面端 (Chrome, Firefox, Safari, Edge)
- ✅ 平板电脑 (iPad, Android Tablet)
- ✅ 手机端 (iOS Safari, Android Chrome)

## 🎯 使用方法

### 1. 发电量预测
1. 输入所在城市
2. 设置光伏板总功率 (kW)
3. 调整安装角度 (度)
4. 填写本地电价 (元/度)
5. 输入系统总成本 (元)
6. 点击"开始预测"

### 2. 角度优化
1. 输入所在地纬度
2. 点击"计算最佳角度"
3. 查看推荐安装角度和优化建议

## 📈 预测算法

系统使用以下因素进行发电量预测：

- **地理因素**: 城市位置、纬度
- **设备参数**: 功率容量、安装角度
- **环境因素**: 太阳辐射、天气条件
- **效率系数**: 角度效率、地区系数

## 🌍 本地开发

如需本地开发，请按以下步骤操作：

```bash
# 克隆项目
git clone https://github.com/yourusername/solar-power-predictor.git

# 进入目录
cd solar-power-predictor

# 安装Vercel CLI
npm i -g vercel

# 本地开发
vercel dev
```

## 🚀 部署到Vercel

### 方法一: 通过Vercel CLI
```bash
# 安装Vercel CLI
npm i -g vercel

# 登录Vercel
vercel login

# 部署
vercel --prod
```

### 方法二: 通过GitHub集成
1. 将代码推送到GitHub仓库
2. 在Vercel中连接GitHub仓库
3. 自动部署

## 📊 系统架构

```
solar-power-predictor/
├── static_web/
│   ├── index.html          # 主页面
│   └── api/               # API接口 (预留)
├── vercel.json            # Vercel配置
├── package.json           # 项目配置
└── README.md             # 说明文档
```

## 🔧 配置说明

### Vercel配置 (vercel.json)
- 静态文件托管
- 路由重写规则
- 预留API接口支持

### 响应式断点
- 桌面端: > 1024px
- 平板端: 768px - 1024px
- 手机端: < 768px

## 📝 更新日志

### v1.0.0 (2024-08-31)
- ✅ 完整的光伏发电量预测功能
- ✅ 经济效益分析计算
- ✅ 安装角度优化工具
- ✅ 响应式现代化界面
- ✅ Vercel部署支持

## 🤝 贡献指南

欢迎提交Issue和Pull Request来改进项目！

1. Fork项目
2. 创建功能分支
3. 提交更改
4. 发起Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 📞 联系我们

- 📧 邮箱: contact@solar-predictor.com
- 🌐 网站: https://your-domain.vercel.app
- 📱 微信: solar-predictor

## 🙏 致谢

感谢以下开源项目：
- [Chart.js](https://www.chartjs.org/) - 图表库
- [Font Awesome](https://fontawesome.com/) - 图标库
- [Inter Font](https://fonts.google.com/specimen/Inter) - 字体
- [Vercel](https://vercel.com/) - 部署平台

---

**让太阳能投资更智能，让绿色能源更普及！** 🌱