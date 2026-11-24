# 이영현 · Lee Younghyun

**Embedded Robotics & Systems Integration Engineer**

전자공학을 전공하고 로봇의 하위 제어기와 상위 소프트웨어를 연결해 왔습니다. 주행 명령을 보냈을 때 바퀴가 어떻게 움직였는지, 통신이 끊겼을 때 어느 신호에서 멈췄는지를 코드와 계측으로 확인합니다.

## 대표 프로젝트 · Tracked Mobile Robot

브라우저로 조종하는 궤도 로봇을 만들었습니다. ESP32-S3가 무선 명령을 전달하고 STM32F446RE가 좌우 모터의 출력을 결정합니다. 펌웨어와 전장·기구를 통합하고, 카펫에서의 주행과 정지, 엔코더 피드백을 확인했습니다.

[![카펫을 전진하는 궤도 로봇과 브라우저에 표시된 좌우 모터 출력·엔코더 값](https://raw.githubusercontent.com/pr0ved99/TIL/refs/heads/agent/dual-encoder-bringup/Projects/Tracked_Mobile_Robot/docs/portfolio/figures/carpet_drive_80s.jpg)](https://raw.githubusercontent.com/pr0ved99/TIL/refs/heads/agent/dual-encoder-bringup/Projects/Tracked_Mobile_Robot/assets/videos/wifi_mvp/2026-10-24/final/TMR_MVP_Final_2026-10-24.mp4)

**[실물 주행 MP4 · 2분 29초](https://raw.githubusercontent.com/pr0ved99/TIL/refs/heads/agent/dual-encoder-bringup/Projects/Tracked_Mobile_Robot/assets/videos/wifi_mvp/2026-10-24/final/TMR_MVP_Final_2026-10-24.mp4)** · [프로젝트와 소스 코드](https://github.com/pr0ved99/TIL/tree/agent/dual-encoder-bringup/Projects/Tracked_Mobile_Robot#readme) · [정지 명령 후 두 PWM이 꺼지는 23.50 µs의 파형](https://github.com/pr0ved99/TIL/blob/agent/dual-encoder-bringup/Projects/Tracked_Mobile_Robot/docs/verification/10_STM32_Active_DISARM_Shutdown_Latency_Test_Report_2026-08-04_ko.md)

## 다른 프로젝트

| 프로젝트 | 제가 다룬 부분 |
| --- | --- |
| [Echo Turtle Navigation](https://github.com/pr0ved99/echo-turtle-navigation/tree/main/edge) | Jetson의 ROS 2 런타임에서 RealSense D435i 토픽을 내보내고, 노트북의 RTAB-Map으로 이어지는 경로를 구성했습니다. |
| [PetNer Robot Platform](https://github.com/pr0ved99/petner-robot-platform/tree/main/hardware) | 메카넘 휠 로봇의 전원 분배, STM32 하위 제어기, 상위 컴퓨터의 UART 인터페이스를 설계했습니다. |
| [세탁물 수거·분류 자동화](https://github.com/pr0ved99/smart-home-laundry-automation) | TurtleBot3, Dobot, 컨베이어와 STM32 그리퍼가 세탁물을 인계하도록 ROS 2와 TCP/IP를 연결했습니다. |
| [STM32 Crane Monitor](https://github.com/pr0ved99/stm32-crane-monitor) | STM32 센서값을 UART로 읽어 Node.js와 Vue 대시보드에 실시간으로 표시했습니다. |
| [적재적소 스마트팩토리](https://github.com/pr0ved99/jeokjaejeokso-smart-factory) | AGV·로봇팔·작업지시 상태를 Django API와 WebSocket을 통해 관제 화면에 연결했습니다. |

<details>
<summary>분야별 사용 기술</summary>

| 분야 | 기술 |
| --- | --- |
| 임베디드·전장 | STM32 HAL, ESP32, UART, CAN, PWM, GPIO, I²C, 모터 제어와 전원 분배 |
| 로봇·인지 | ROS 2 Humble/Jazzy, Nav2, RTAB-Map, Gazebo, Isaac Sim, D435i, YOLOv8, OpenCV |
| 기구·컴퓨팅 | Onshape, 3D 프린팅, Raspberry Pi, NVIDIA Jetson |
| 관제·배포 | Node.js, Vue, Django, WebSocket, Socket.IO, PostgreSQL, Docker, Jenkins |

</details>

## 학습과 연구

- SSAFY 임베디드 로봇 트랙에서 임베디드·ROS 2 통합 프로젝트를 수행했습니다. [기술 학습 기록](https://github.com/pr0ved99/TIL)
- 삼성 SW 역량테스트 A+를 취득했습니다. [C++ 알고리즘 풀이](https://github.com/pr0ved99/daily-algorithm) · [solved.ac](https://solved.ac/profile/eyh125)
- 졸업 연구에서 SFG 기반 유전율 산출 알고리즘을 설계하고 오차율 0.21% 미만을 달성했습니다.

[이메일 · eyh125@gmail.com](mailto:eyh125@gmail.com)
