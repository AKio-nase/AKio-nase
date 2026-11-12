# 嵌入式 / 端-云 / 网页

做 ESP32 端到云的项目，也写网页前端和 PLC 程序。

> 本页仅用于个人作品展示；下列仓库未经许可不得用于商业用途。

## 项目

**[oximeter-esp32-cloud](https://github.com/AKio-nase/oximeter-esp32-cloud)**
MAX30102 采血氧和心率，ESP32 通过 MQTTS 上云，浏览器实时看数。固件、监控页、接线图都在仓库里。

**[plc-fc9-review](https://github.com/AKio-nase/plc-fc9-review)**
西门子 PLC 程序的逐网络审查。4 工位转盘扫码线，FC9 自动模块 RFID，整理出 8 处会导致误动作的地方，每条给出网络号和改法。

**[face_detector](https://github.com/AKio-nase/face_detector)**
用 OpenCV 写的人脸检测命令行工具。图片 / 摄像头 / 视频三种输入，可以打码、裁脸、导出 JSON。

## 在用的东西

- **嵌入式**：C（51 单片机、ESP32 / Arduino）、I2C 与 UART 设备驱动、74HC595 级联、ADC 采样与滑动平均
- **网页**：HTML / CSS / 原生 JavaScript、mqtt.js over WSS、ECharts、Mermaid
- **工业**：西门子 PLC（TIA Portal）、梯形图、数据块读写
- **其他**：Python、Git
