# Lee Younghyun
### Embedded Robotics & Systems Integration Engineer

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=180&section=header&text=Hardware%20to%20Autonomy&fontColor=ffffff&fontSize=42&desc=STM32%20%7C%20ROS%202%20%7C%20Edge%20AI%20%7C%20Web%20Monitoring&descAlignY=70&descSize=16" width="100%"/>
</div>

안녕하세요. 전자공학 기반의 하드웨어 이해를 바탕으로, **MCU 펌웨어부터 ROS 2 자율주행, Edge AI, 웹 모니터링까지 데이터가 끊기지 않는 시스템**을 구축하는 이영현입니다.

제가 집중하는 지점은 단순히 한 기능을 구현하는 것이 아니라, 센서와 액추에이터, 로봇 미들웨어, 네트워크, 대시보드가 하나의 흐름으로 동작하도록 통합하고 검증하는 일입니다.

---

## What I Build

- **Embedded Control**: STM32 HAL 기반 UART, PWM, GPIO, I2C 제어와 센서/액추에이터 통합
- **Robotics Autonomy**: ROS 2, Nav2, RTAB-Map, Gazebo 기반 실내 주행 및 시뮬레이션 검증
- **Edge AI Pipeline**: Jetson/Raspberry Pi 환경에서 RealSense, YOLO, ROS 2 topic 파이프라인 구성
- **Monitoring & Operations**: Node.js, Vue.js, Django, WebSocket 기반 실시간 상태 시각화

---

## Featured Projects

| Project | System Focus | Core Stack |
| :--- | :--- | :--- |
| [echo-turtle-navigation](https://github.com/pr0ved99/echo-turtle-navigation) | Jetson 기반 ROS 2 로봇 런타임, D435i 카메라 topic, RTAB-Map/VSLAM, Nav2/Gazebo 검증 흐름 정리 | ROS 2, Jetson, RealSense D435i, RTAB-Map, Nav2, Gazebo, YOLO, Docker |
| [petner-robot-platform](https://github.com/pr0ved99/petner-robot-platform) | 4WD 메카넘 휠 로봇의 전원 구조, STM32 하위 제어, UART 기반 상위 제어기 연동, LiDAR/AI 컴퓨팅 계층 설계 | STM32F446RE, Raspberry Pi 5, Jetson Orin Nano, UART, LiDAR, Mecanum Drive, MQTT |
| [smart-home-laundry-automation](https://github.com/pr0ved99/smart-home-laundry-automation) | TurtleBot3, Dobot, Conveyor를 연결한 세탁물 수거/분류 자동화와 ROS 2 Topic, TCP/IP Socket, STM32 그리퍼 통합 | ROS 2 Humble, TurtleBot3, Dobot, STM32, Raspberry Pi, Nav2, YOLOv8, OpenCV |
| [stm32-crane-monitor](https://github.com/pr0ved99/stm32-crane-monitor) | STM32 센서 데이터를 UART에서 Node.js 미들웨어와 Vue.js 대시보드까지 전달하는 저지연 모니터링 파이프라인 | STM32F103RB, C, HAL, UART 115200, Node.js, SerialPort, Socket.IO, Vue 3 |
| [jeokjaejeokso-smart-factory](https://github.com/pr0ved99/jeokjaejeokso-smart-factory) | 스마트팩토리 관제용 Django/Vue 대시보드, AGV/로봇팔/작업지시 상태 API, WebSocket, 배포 파이프라인 구성 | Django, Vue 3, Vuetify, PostgreSQL, WebSocket, Docker, Jenkins |

---

## Technical Stack

<p>
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/>
  <img src="https://img.shields.io/badge/NVIDIA-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gazebo-F58113?style=flat-square&logo=gazebo&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white"/>
  <img src="https://img.shields.io/badge/Onshape-1B5FAA?style=flat-square&logo=onshape&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</p>

| Area | Keywords |
| :--- | :--- |
| Embedded & Hardware | STM32, ESP32, Raspberry Pi, Jetson, UART, CAN, PWM, GPIO, I2C, motor control, power distribution |
| Robotics & Autonomy | ROS 2 Humble/Jazzy, Nav2, RTAB-Map, Gazebo, Isaac Sim, TF, odometry, costmap tuning |
| AI & Perception | RealSense D435i, YOLOv8, OpenCV, RGB-D topic pipeline, object 3D coordinate estimation |
| CAD & Mechanical | Onshape, 3D printed gripper/lift structure, robot frame and sensor mounting |
| Web & Infrastructure | Node.js, Vue.js, Django, WebSocket, Socket.IO, PostgreSQL, Docker, Jenkins |

---

## Proof Points

- **Samsung SW Competency Test A+ Grade**: C++ 기반 알고리즘 최적화 역량
- **SSAFY Embedded Robot Track**: 임베디드, ROS 2, 로봇 통합 프로젝트 수행
- **Graduation Research**: SFG 기반 유전율 산출 알고리즘 설계, 오차율 0.21% 미만 달성

<p align="left">
  <a href="https://solved.ac/eyh125">
    <img src="http://mazassumnida.wtf/api/generate_badge?boj=eyh125" height="120px" />
  </a>
</p>

---

## Contact

<p align="left">
  <a href="mailto:eyh125@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://solved.ac/eyh125"><img src="https://img.shields.io/badge/Solved.ac-17CE3A?style=flat-square&logo=solveddotac&logoColor=white"/></a>
  <a href="https://github.com/pr0ved99"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
</p>
