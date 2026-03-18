<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

# 🙋‍♀️ HomeBe : AI Smart Home Assistant

독거노인을 위한 **AI 스마트 홈비서 시스템** 프로젝트입니다.  
STM32, Raspberry Pi, AWS, React를 기반으로 구성되었으며,  
실시간 센서 모니터링, 낙상 감지, 사용자 알림 및 원격 확인 기능을 목표로 합니다.

---

## ✍️ Overview

HomeBe는 독거노인의 일상 안전과 생활 보조를 위한 스마트 홈 케어 시스템입니다.  
센서 데이터와 영상 정보를 바탕으로 위험 상황을 감지하고,  
사용자와 보호자가 상태를 쉽게 확인할 수 있도록 시스템을 설계했습니다.

이 프로젝트는 다음과 같은 흐름으로 동작합니다.

- **STM32** : 모터 및 장치 제어, UART 통신
- **Raspberry Pi** : 카메라 처리 및 AI 기반 상황 인식
- **Raspberry Pi** : 센서값 수집
- **AWS** : 데이터 저장, 이벤트 처리, 알림 전송
- **Web/App** : 사용자 상태 확인 및 모니터링 화면 제공

---

## ⚙ System Architecture

<p align = "center">
<img width="552" height="300" alt="Image" src = "https://github.com/user-attachments/assets/e61966a8-ce0b-420a-b291-2ea0a60badbe">
</p>

> 전체 시스템은 센서 및 제어부, AI 처리부, 클라우드 서버, 사용자 인터페이스, 보호자용 어플리케이션으로 구성됩니다.

---

## ✍️ Key Features

- 낙상 및 이상 상황 감지
- 환경 센서 기반 상태 모니터링
- UART 기반 명령 송수신
- 보호자 알림 및 상태 공유
- 웹 기반 모니터링 인터페이스
- 스마트 홈 보조 기능 연동

---
## ⚙ Tech Stack

| Category | Stack |
|---|---|
| **Embedded / Device** | ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![NUCLEO Board](https://img.shields.io/badge/NUCLEO_Board-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![HAL Library](https://img.shields.io/badge/HAL_Library-00979D?style=flat-square) ![UART](https://img.shields.io/badge/UART-555555?style=flat-square) ![Timer Interrupt](https://img.shields.io/badge/Timer_Interrupt-555555?style=flat-square) ![PWM](https://img.shields.io/badge/PWM-555555?style=flat-square) ![EXTI](https://img.shields.io/badge/EXTI-555555?style=flat-square) |
| **Sensors** | ![Raspberry Pi 4](https://img.shields.io/badge/Raspberry_Pi_4-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![DHT22](https://img.shields.io/badge/DHT22-4CAF50?style=flat-square) ![MQ-2](https://img.shields.io/badge/MQ--2-4CAF50?style=flat-square) ![MQ-7](https://img.shields.io/badge/MQ--7-4CAF50?style=flat-square) ![Sensor Interface](https://img.shields.io/badge/Sensor_Interface-4CAF50?style=flat-square) |
| **Edge / AI** | ![Raspberry Pi 4](https://img.shields.io/badge/Raspberry_Pi_4-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Webcam](https://img.shields.io/badge/Webcam-666666?style=flat-square) ![MediaPipe Pose](https://img.shields.io/badge/MediaPipe_Pose-FF6F00?style=flat-square) ![AI Detection](https://img.shields.io/badge/AI--based_Detection-8E44AD?style=flat-square) |
| **Cloud / Backend** | ![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white) ![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square) ![API](https://img.shields.io/badge/API-2C3E50?style=flat-square) ![Notification Processing](https://img.shields.io/badge/Notification_Processing-E67E22?style=flat-square) |
| **Web Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Dashboard UI](https://img.shields.io/badge/Dashboard_UI-2D8CFF?style=flat-square) ![Real-time Monitoring](https://img.shields.io/badge/Real--time_Monitoring-16A085?style=flat-square) |
| **Mobile App** | ![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white) ![REST API](https://img.shields.io/badge/REST_API-009688?style=flat-square) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |

---

## 🔗 Repositories

| Repository | Description |
|---|---|
| [Sensor / RaspberryPi ](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-Sensor) | 프로젝트 전체 소개 및 문서 정리 |
| [Embedded / STM32](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-STM32) | STM32 기반 센서 제어 및 장치 동작 |
| [AI / Raspberry Pi](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-Detection_model) | 영상 처리 및 AI 기능 구현 |
| [Backend / AWS](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-AWS) | 클라우드 연동 및 데이터 처리 |
| [Frontend / Web](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-React) | 사용자 모니터링 웹 화면 |
| [APP](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-APP) | 보호자 및 사용자용 앱 구성 |

---

## ✍️ Project Goals

이 프로젝트는 단순한 센서 수집 시스템이 아니라,  
**위험 감지 → 정보 전달 → 사용자 확인 → 대응 보조**까지 연결되는  
통합형 스마트 홈 케어 시스템을 목표로 합니다.

특히 다음과 같은 방향을 중점으로 개발했습니다.

- 고령자 안전 보조
- 직관적인 상태 확인
- 실시간 데이터 연동
- 임베디드와 AI의 융합
- 실제 적용 가능한 구조 설계

---

## DemoPhoto

<p align = "center">
<img width="197" height="358" alt="Image" src="https://github.com/user-attachments/assets/5498ddbc-bd99-430e-bdc2-be53ce2f2602" />
</p>

<div align=center>
	<구현된 독거노인 AI 홈비서 로봇 외형>
</div>

---

## DemoVideo

Click the image below to watch the demo video on YouTube.

[![HomeBe Demo](https://github.com/user-attachments/assets/d7fb46c1-d3e5-4da3-82c8-dd58e6757cc7)](https://www.youtube.com/watch?v=bdJWRNAsrWQ)

<div align=center>
	<DemoVideo>
</div>
		
---

## Team

**HomeBe Team**  
AI Smart Home Assistant Project

- Embedded System Development
- AI / Edge Computing
- Cloud Backend
- Frontend & Monitoring UI
- APP Devlopment

---

## Contact

For project information, please check each repository or the project documentation above.
