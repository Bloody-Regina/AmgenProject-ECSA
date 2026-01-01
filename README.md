# AmgenProject-ECSA

一个前端单页的农业智能助手演示页面，集成天气查询、作物推荐、市场信息与 AI 农业建议展示。

## 功能
- 城市天气查询（OpenWeatherMap）
- 天气联动作物推荐与适宜度展示
- 市场与季节信息展示（示例数据）
- AI 农业建议展示（OpenAI API）
- 病害风险与高级功能提示（示例/占位）

## 运行方式
直接用浏览器打开 `Agros AI V0.html` 即可使用。

## 配置
在 `Agros AI V0.html` 中替换以下 API Key：
- `apiKey`: OpenWeatherMap API Key
- `openaiApiKey`: OpenAI API Key

建议将 Key 改为通过环境变量或后端代理提供，避免前端明文暴露。

## 结构
- `Agros AI V0.html`: 主页面与全部前端逻辑
- `README.md`: 项目说明

## 免责声明
本项目为演示用途，市场数据与病害建议为示例/占位内容，不可作为生产决策依据。

