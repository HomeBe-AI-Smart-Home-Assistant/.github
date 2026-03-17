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

![System Architecture](여기에_구성도_이미지_URL_넣기)

> 전체 시스템은 센서 및 제어부, AI 처리부, 클라우드 서버, 사용자 인터페이스로 구성됩니다.

---

## ✍️ Key Features

- 낙상 및 이상 상황 감지
- 환경 센서 기반 상태 모니터링
- UART 기반 명령 송수신
- 보호자 알림 및 상태 공유
- 웹 기반 모니터링 인터페이스
- 스마트 홈 보조 기능 연동

---
<!-- 표로 나타내면 더욱 좋을 듯 -->
## ⚙ Tech Stack

### Embedded / Device
- STM32 NUCLEO Board
- HAL Library
- UART / Timer Interrupt / PWM / EXTI

- Raspberry Pi 4
- Sensor Interface
- DHT22 / MQ-2 / MQ-7

### Edge / AI
- Raspberry Pi 4
- Python
- Web Camera
- AI-based Detection
- MediaPipePose

### Cloud / Backend
- AWS Lambda
- DynamoDB
- MQTT
- API / Notification Processing

### Frontend
- React
- Dashboard UI
- Real-time Monitoring

### Frontend
- Android Studio
- Rest API
- FireBase

---

## 🔗 Repositories

| Repository | Description |
|---|---|
| [Sensor / RaspberryPi ](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-Sensor) | 프로젝트 전체 소개 및 문서 정리 |
| [Embedded / STM32](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-STM32) | STM32 기반 센서 제어 및 장치 동작 |
| [AI / Raspberry Pi](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-Detection_model) | 영상 처리 및 AI 기능 구현 |
| [Backend / AWS](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-AWS) | 클라우드 연동 및 데이터 처리 |
| [Frontend / Web](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-React) | 사용자 모니터링 웹 화면 |
| [Frontend / Web](https://github.com/HomeBe-AI-Smart-Home-Assistant/AI-Home-Assistance-App) | 보호자 및 사용자용 앱 구성 |

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

## Demo

![Demo Image 1](여기에_데모이미지1_URL_넣기)
![Demo Image 2](여기에_데모이미지2_URL_넣기)

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
