# 城市标志图像说明

## 概述
此文件说明如何为天气预报网页添加杭州和西安的官方城市标志。

## 图像要求
- 文件名: `hangzhou-logo.png` (杭州城市标志)
- 文件名: `xian-logo.png` (西安城市标志)
- 格式: PNG (推荐透明背景)
- 尺寸: 建议 30x30 像素 (可根据需要调整)

## 存放位置
请将图像文件放在以下目录：
```
workspace/
└── images/
    ├── hangzhou-logo.png
    └── xian-logo.png
```

## 已更新的文件
以下HTML文件已更新，包含城市标志的图像引用：
- `index.html`
- `weather_real.html`
- `weather_forecast_chinese.html`

## 图像引用示例
```html
<h2><img src="./images/hangzhou-logo.png" alt="杭州" class="city-logo" width="30" height="30">杭州</h2>
<h2><img src="./images/xian-logo.png" alt="西安" class="city-logo" width="30" height="30">西安</h2>
```

## CSS样式
已添加以下CSS样式以确保图像正确显示：
```css
.city-logo {
    vertical-align: middle;
    border-radius: 4px;
    margin-right: 8px;
}
```

## 注意事项
1. 确保图像文件路径正确
2. 推荐使用透明背景的PNG格式图像
3. 图像大小不宜过大，以免影响页面加载速度
4. 如果需要调整图像尺寸，可以修改width和height属性或通过CSS调整