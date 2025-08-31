# 天气API配置说明

## 🔑 API密钥配置

为了获取实时天气数据，您需要配置天气API密钥。推荐使用 OpenWeatherMap API。

### 1. 获取API密钥

1. 访问 [OpenWeatherMap](https://openweathermap.org/api)
2. 注册免费账户
3. 获取您的API密钥

### 2. 配置API密钥

在 `app.py` 文件的第 45 行，将 `YOUR_API_KEY_HERE` 替换为您的实际API密钥：

```python
API_KEY = "your_actual_api_key_here"  # 请替换为您的实际API密钥
```

### 3. 免费额度

OpenWeatherMap 免费计划提供：
- 每分钟60次调用
- 每月1,000,000次调用
- 当前天气数据
- 5天天气预报

### 4. 备用方案

如果没有配置API密钥，应用会自动使用模拟天气数据，确保系统正常运行。

## ⚠️ 重要提醒

请在部署到生产环境前配置真实的API密钥，以获得准确的天气数据和预测结果。







