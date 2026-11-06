### Hi, I'm Sukrit 👋

I build practical AI for the electricity sector at **EGAT** (Electricity Generating Authority of Thailand): fault detection for EV chargers, OCPP charging platforms, private on-premise LLM tools, and forecasting and predictive-maintenance models for power assets.

- ⚡ **Now:** packet-level fault detection for DC EV chargers (DIN 70121 / ISO 15118) and OCPP charging-station management
- 🖥️ **Side project:** a local, bilingual Thai/English LLM workbench (llama.cpp + Qwen + MCP)
- 🤝 **Looking for:** contributors and testers, in Thai or English. Beginners are welcome ([see below](#contribute))
- 🎓 Electrical Engineering: Chulalongkorn University (2019) · Kasetsart University (2014)

## Featured projects

| Project | What it does | Built with |
|---|---|---|
| ⚡ **[EV Charger Fault Detection AI](https://github.com/SukritJaAIproject/EV_Charger_Fault_Detection_AI)** | Offline Windows app: open a DC charging-session capture (DIN 70121 / ISO 15118-2) and get the verdict, fault family, packet evidence and who stopped the session. Five detector architectures benchmarked on a 212-station fleet (40,000+ charging sessions). | Python · PyTorch · scikit-learn · TShark · TypeScript |
| 🖥️ **[Qwen Local AI Workbench](https://github.com/SukritJaAIproject/Qwen-Local-AI-Workbench)** | Privacy-first AI workbench for Windows: Thai/English chat UI, per-project workspaces, 50 guarded MCP tools, OCR and semantic document search, voice input and automatic eGPU placement. Models, files and search run on 127.0.0.1. | llama.cpp · Qwen · MCP · Python |
| 🔌 **[BPC EV Charging Platform (CSMS)](https://github.com/SukritJaAIproject/bpc-csms-cloud)** | Charging-station management system for Bhutan Power Corporation: operator console, customer web app, scan-to-pay page and an OCPP 1.6-J server in one Docker container. | Python · aiohttp · OCPP · MongoDB · Docker |

<p>
  <a href="https://github.com/SukritJaAIproject/EV_Charger_Fault_Detection_AI"><img src="https://raw.githubusercontent.com/SukritJaAIproject/EV_Charger_Fault_Detection_AI/main/docs/images/pcap-analysis.png" width="49%" alt="EV Charger Fault Detection AI: PCAP analysis result with verdict, fault family and packet evidence"></a>
  <a href="https://github.com/SukritJaAIproject/Qwen-Local-AI-Workbench"><img src="https://raw.githubusercontent.com/SukritJaAIproject/Qwen-Local-AI-Workbench/main/docs/screenshots/01-chat-en-dark.png" width="49%" alt="Qwen Local AI Workbench: chat in a project with a summary table built from a project file"></a>
</p>

## Earlier work (2018–2024)

- 🏆 **7th prize, AIAT × Kaggle Hackathon 1/2020 (COVID image):** [7_Hackathon_1_2020_Covid_Image](https://github.com/SukritJaAIproject/7_Hackathon_1_2020_Covid_Image)
- 🏥 **AI CARE:** facial landmarks, action units, eye and upper-body movement for patient emotion monitoring: [AICARE](https://github.com/SukritJaAIproject/AICARE) · [kaimook](https://github.com/SukritJaAIproject/kaimook) · [corpus_dataset](https://github.com/SukritJaAIproject/corpus_dataset)
- 💧 **Hydropower and dams:** CNN forecasting of reservoir water storage and dam predictive maintenance: [4_Reservoir_Water_Storage_Forecasting](https://github.com/SukritJaAIproject/4_Reservoir_Water_Storage_Forecasting_of_VRK_dam_using_CNN) · [12_SNR_Dam_Predictive_Maintenance](https://github.com/SukritJaAIproject/12_SNR_Dam_Predictive_Maintenance_matlab)
- ☀️ **Solar and weather:** PV power forecasting from weather forecasts, solar forecasting with RNNs, weather-API data collection: [IoT_Fundamentals](https://github.com/SukritJaAIproject/IoT_Fundamentals) · [AICU_2018](https://github.com/SukritJaAIproject/AICU_2018) · [weather_api](https://github.com/SukritJaAIproject/weather_api)
- 🏠 **Smart energy:** behind-the-meter Livable Showroom IoT platform, reinforcement learning for energy management, ESP32 air-conditioner remote: [livableshowroom](https://github.com/SukritJaAIproject/livableshowroom) · [11_RL_EMS](https://github.com/SukritJaAIproject/11_RL_EMS) · [16_ESP32_EL_AirCon_Remote_1](https://github.com/SukritJaAIproject/16_ESP32_EL_AirCon_Remote_1)
- 🔧 **Predictive maintenance and vision for power assets:** breaker-sound clustering, transformer camera data, power-meter reading, bird detection in substations: [2_Audio_Signal_Clustering](https://github.com/SukritJaAIproject/2_Audio_Signal_Clustering) · [13_Transformers_Pdm](https://github.com/SukritJaAIproject/13_Transformers_Pdm) · [9_Reading_Power_Meter_CNN](https://github.com/SukritJaAIproject/9_Reading_Power_Meter_CNN) · [Birdinsubstation_detection](https://github.com/SukritJaAIproject/Birdinsubstation_detection)

## Contribute

New to open source? These issues are a good place to start:

- [Qwen Local AI Workbench: good first issues](https://github.com/SukritJaAIproject/Qwen-Local-AI-Workbench/labels/good%20first%20issue)
- [EV Charger Fault Detection AI: good first issues](https://github.com/SukritJaAIproject/EV_Charger_Fault_Detection_AI/labels/good%20first%20issue)

Bug reports, questions and pull requests are welcome in Thai or English.

## Tech

Python · PyTorch · TensorFlow/Keras · scikit-learn · OpenCV · llama.cpp · MCP · OCPP · DIN 70121 / ISO 15118 · Docker · MongoDB · MATLAB · ESP32/Arduino

## Elsewhere

- Kaggle: [kaggle.com/sukitch](https://www.kaggle.com/sukitch)

---

### 🇹🇭 ภาษาไทย

สวัสดีครับ ผมพัฒนา AI สำหรับระบบไฟฟ้าและสถานีชาร์จรถยนต์ไฟฟ้าที่ กฟผ.

- **EV Charger Fault Detection AI:** โปรแกรม Windows วิเคราะห์ไฟล์ PCAP ของการชาร์จแบบ DC (DIN 70121 / ISO 15118-2) แล้วบอกผลการตรวจ กลุ่มความผิดปกติ หลักฐานจากแพ็กเก็ต และฝ่ายที่หยุดการชาร์จ ทำงานได้โดยไม่ต้องต่ออินเทอร์เน็ต
- **Qwen Local AI Workbench:** ระบบ AI ที่รันบนเครื่องของตัวเอง หน้าจอภาษาไทย/อังกฤษ แยกงานเป็นโปรเจกต์ มีเครื่องมือ MCP ที่ต้องยืนยันก่อนรัน อ่านเอกสารสแกนภาษาไทยด้วย OCR และค้นเอกสารตามความหมาย
- **BPC EV Charging Platform:** ระบบบริหารสถานีชาร์จ (CSMS) พร้อมแอปลูกค้า หน้าชำระเงินผ่าน QR และเซิร์ฟเวอร์ OCPP 1.6

ยินดีรับ issue คำถาม และ pull request ทั้งภาษาไทยและภาษาอังกฤษ ถ้าเพิ่งเริ่มร่วมพัฒนาโอเพนซอร์ส เริ่มจาก issue ที่ติดป้าย **good first issue** ได้เลยครับ
