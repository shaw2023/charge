# ⚡️ 充电时长模型 (Charging Duration Simulator)

一个基于**双线性插值算法**与**集中参数热模型**的电动汽车充电仿真工具。通过模拟微积分过程，精确预测在不同温度、SOC 起始点及电池物理特性下的充电表现。

🌐 **在线访问:** [charge.samaritan.dpdns.org](https://charge.samaritan.dpdns.org)

---

## 🚀 核心功能

* **双线性插值计算**：支持自定义上传 Excel 格式的充电 Map 矩阵（温度 × SOC），实现电流数据的平滑推算。
* **集中参数热模型**：集成电池温升模拟，考虑电池质量、比热容、内阻及热阻对充电过程的影响。
* **实时过程可视化**：基于 ECharts 构建，动态展示 SOC 曲线、电流衰减及温度变化。
* **本地配置管理**：支持保存多个充电 Map 及温升模型配置到本地浏览器缓存。
* **专业报告导出**：一键生成详细的仿真参数与计算结果摘要。

## 🛠️ 技术栈

* **Core**: Vanilla JavaScript (ES6+)
* **Algorithm**: Bilinear Interpolation & Calculus Simulation
* **Visualization**: [Apache ECharts](https://echarts.apache.org/)
* **Styling**: CSS3 (Modern Flex/Grid, FontAwesome)

## 📖 使用指南

1.  **配置 Map**：点击“配置充电map”，将 Excel 中的电流矩阵粘贴至输入框。
2.  **设定热参数**：进入“温升模型配置”，输入电池质量、比热容等物理参数以启用温度仿真。
3.  **调整环境**：通过滑动条精确控制起始 SOC、目标 SOC 及环境温度。
4.  **执行仿真**：点击“计算”即可获得预计时长及全程电流走势图。

---

### 📦 部署信息
本项目托管于 GitHub Pages。

---
*Developed by Shaw*
