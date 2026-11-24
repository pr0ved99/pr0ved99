# 이영현 · Lee Younghyun

**Embedded Robotics & Systems Integration Engineer**

전자공학을 전공하고 STM32로 모터와 그리퍼를 제어하는 펌웨어, 카메라로 위치를 추정하고 목표까지 주행하는 로봇 소프트웨어를 개발해 왔습니다. 주행 명령을 보냈을 때 바퀴가 어떻게 움직였는지, 통신이 끊겼을 때 어느 신호에서 멈췄는지를 코드와 계측으로 확인합니다.

## 대표 프로젝트 · Tracked Mobile Robot

브라우저로 조종하는 궤도 로봇을 만들었습니다. ESP32-S3가 무선 명령을 전달하고 STM32F446RE가 좌우 모터의 출력을 결정합니다. 펌웨어와 전장·기구를 통합하고, 카펫에서의 주행과 정지, 엔코더 피드백을 확인했습니다.

[![카펫을 전진하는 궤도 로봇과 브라우저에 표시된 좌우 모터 출력·엔코더 값](https://raw.githubusercontent.com/pr0ved99/TIL/refs/heads/agent/dual-encoder-bringup/Projects/Tracked_Mobile_Robot/docs/portfolio/figures/carpet_drive_80s.jpg)](https://raw.githubusercontent.com/pr0ved99/TIL/refs/heads/agent/dual-encoder-bringup/Projects/Tracked_Mobile_Robot/assets/videos/wifi_mvp/2026-10-24/final/TMR_MVP_Final_2026-10-24.mp4)

**[실물 주행 MP4 · 2분 29초](https://raw.githubusercontent.com/pr0ved99/TIL/refs/heads/agent/dual-encoder-bringup/Projects/Tracked_Mobile_Robot/assets/videos/wifi_mvp/2026-10-24/final/TMR_MVP_Final_2026-10-24.mp4)** · [프로젝트와 소스 코드](https://github.com/pr0ved99/TIL/tree/agent/dual-encoder-bringup/Projects/Tracked_Mobile_Robot#readme) · [정지 명령 후 두 PWM이 꺼지는 23.50 µs의 파형](https://github.com/pr0ved99/TIL/blob/agent/dual-encoder-bringup/Projects/Tracked_Mobile_Robot/docs/verification/10_STM32_Active_DISARM_Shutdown_Latency_Test_Report_2026-08-04_ko.md)

## 다른 프로젝트

| 프로젝트 | 제가 맡은 역할 |
| --- | --- |
| [Echo Turtle Navigation](https://github.com/pr0ved99/echo-turtle-navigation/tree/main/edge) | **VSLAM과 자율주행**을 담당했습니다. RealSense D435i와 RTAB-Map으로 로봇의 위치를 추정하고 지도를 만드는 기능, Nav2로 목표 지점까지 주행하는 기능을 구현했습니다. |
| [PetNer Robot Platform](https://github.com/pr0ved99/petner-robot-platform/tree/main/hardware) | **로봇 하드웨어와 STM32 펌웨어**를 설계했습니다. 메카넘 휠 로봇의 전원 분배와 모터·센서 배선을 구성하고 STM32 하위 제어기를 개발했습니다. [펌웨어](https://github.com/pr0ved99/petner-robot-platform/tree/main/embedded) |
| [세탁물 수거·분류 자동화](https://github.com/pr0ved99/smart-home-laundry-automation) | **그리퍼와 STM32 펌웨어**를 설계했습니다. 카메라로 세탁물을 인식하면 그리퍼가 집고, TurtleBot3가 Nav2로 수거 지점까지 운반하는 동작을 구현했습니다. [인식·파지 제어 코드](https://github.com/pr0ved99/smart-home-laundry-automation/blob/main/ros2-turtlebot-nav/final_patrol_grip.py) |
| [STM32 Crane Monitor](https://github.com/pr0ved99/stm32-crane-monitor) | **단독 개발**했습니다. STM32 센서 수집 펌웨어부터 UART 데이터를 받는 Node.js 서버, 값을 실시간으로 보여주는 Vue 대시보드까지 전체 시스템을 구현했습니다. |
| [적재적소 스마트팩토리](https://github.com/pr0ved99/jeokjaejeokso-smart-factory/tree/main/sim/arm/scripts) | **로봇팔의 상자 배치와 강화학습**을 담당했습니다. 목표 위치에 상자를 놓는 동작을 먼저 스크립트로 구현한 뒤, 같은 작업을 학습하도록 단계별 강화학습 실험을 진행했습니다. [학습 기록](https://github.com/pr0ved99/jeokjaejeokso-smart-factory/tree/main/sim/arm/docs/training_journal) |

<details>
<summary>분야별 사용 기술</summary>

| 분야 | 기술 |
| --- | --- |
| 임베디드·전장 | STM32 HAL, ESP32, UART, CAN, PWM, GPIO, I²C, 모터 제어와 전원 분배 |
| 자율주행·인지 | ROS 2 Humble/Jazzy, Nav2, RTAB-Map 기반 VSLAM, D435i, YOLOv8, OpenCV |
| 시뮬레이션·강화학습 | Gazebo 주행 검증, Isaac Sim 로봇팔 상자 배치 실험 |
| 기구·컴퓨팅 | Onshape, 3D 프린팅, Raspberry Pi, NVIDIA Jetson |
| 실시간 모니터링 | UART 센서 수집, Node.js, Socket.IO, Vue |
| 웹·개발 환경 | Django, WebSocket, PostgreSQL, Docker, Jenkins |

</details>

## 학습과 연구

- SSAFY 임베디드 로봇 트랙에서 임베디드·ROS 2 통합 프로젝트를 수행했습니다. [기술 학습 기록](https://github.com/pr0ved99/TIL)
- 삼성 SW 역량테스트 A+를 취득했습니다. [C++ 알고리즘 풀이](https://github.com/pr0ved99/daily-algorithm) · [solved.ac](https://solved.ac/profile/eyh125)
- 졸업 연구에서 SFG 기반 유전율 산출 알고리즘을 설계하고 오차율 0.21% 미만을 달성했습니다.

[이메일 · eyh125@gmail.com](mailto:eyh125@gmail.com)
