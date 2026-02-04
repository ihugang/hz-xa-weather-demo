# 杭州-西安天气预报应用

一个简洁美观的天气预报应用，展示杭州和西安的天气信息。

## 功能特色

- 🌤️ 实时天气信息展示
- 📅 今明两天天气预报
- 🌐 中英文双语支持
- 📱 响应式设计，支持移动设备
- 🗺️ 杭州和西安双城市天气对比

## 页面说明

- `index.html` - 主页，展示今明两天的天气预报
- `weather_forecast_chinese.html` - 详细的中文天气预报（使用真实API数据）
- `weather_real.html` - 真实天气数据版（使用API获取实时数据）
- `README.md` - 项目说明文档

## 技术栈

- HTML5
- CSS3
- JavaScript
- Chart.js (用于数据可视化)
- OpenWeatherMap API (用于真实天气数据)

## 使用说明

1. 直接在浏览器中打开任意HTML文件即可查看
2. 如需使用真实天气数据功能，请获取OpenWeatherMap API密钥并替换代码中的占位符

## API密钥配置

**安全提示：出于安全考虑，API密钥不应在客户端代码中硬编码。**

要使用真实天气数据功能，请按照以下步骤操作：

1. 前往 [OpenWeatherMap](https://openweathermap.org/api) 获取免费API密钥
2. 在每个HTML文件中，将 `YOUR_API_KEY_HERE` 替换为您的实际API密钥
3. 对于生产环境，建议使用后端服务器代理API请求以保护API密钥

## 安全最佳实践

- 不要在公共代码库中暴露API密钥
- 考虑使用后端代理服务器来转发API请求
- 定期轮换API密钥
- 限制API密钥的使用范围和权限

## 许可证

本项目为开源项目，可自由使用和修改。