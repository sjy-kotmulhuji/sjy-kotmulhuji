<h1 align="center">🐝 송주연 / Song Juyeon</h1>
<h3 align="center">
  <code>RTL DESIGN</code> · <code>VERIFICATION</code> · <code>FPGA</code> · <code>Embedded</code>
</h3>

---
### 👩‍🦰 About me
- 🎓 경기대학교 전자공학과 졸업(2020/03~2025/08)
- 💌 E-Mail: sjy010805@gmail.com

### 👩‍🎓 Training
| Program & Period| Institution | Details |
| :--- | :--- | :--- |
| **온디바이스AI 시스템 반도체 설계 1기 <br> `2026.01.20 ~ 2026.08.24 (980h)`** | 대한상공회의소 서울기술교육센터 | - Verilog HDL 기반 디지털 회로 및 SoC 설계 <br> - UVM 기반 검증 환경 구축 및 프로젝트 수행 <br> - C, Python 기반 임베디드 시스템 설계 |
| **시스템 반도체 RTL 설계 교육 <br> `2025.11.3 ~ 2025.11.28 (120h)`** | 한국반도체아카데미 | - 반도체 설계 기초 이론 <br> - Verilog RTL 설계, FPGA 보드 실습 |
| **반도체 장비 설계 전문가 양성과정 <br> `2025.06.23~2025.08.29 (300h)`** | 한국반도체아카데미 | - 장비 설계 이론 및 PECVD 장비 설계 프로젝트 |

### 💛 Interest
- RTL Design Engineer
- Verification Engineer
- Firmware/Embedded SW Engineer
---

### 🛠️ Skills

| Category | Badges |
| :--- | :--- |
| **HDL / Verification** | ![SystemVerilog](https://img.shields.io/badge/SystemVerilog-00BCD4?style=for-the-badge&logo=IEEE&logoColor=white) ![Verilog HDL](https://img.shields.io/badge/Verilog%20HDL-1E90FF?style=for-the-badge&logoColor=white) ![Vivado](https://img.shields.io/badge/AMD%20Vivado-1E4620?style=for-the-badge&logo=amd&logoColor=white) <br> ![UVM](https://img.shields.io/badge/UVM-FFD700?style=for-the-badge) ![Linux](https://img.shields.io/badge/LINUX(CLI)%20-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![VCS](https://img.shields.io/badge/Synopsys%20VCS-000000?style=for-the-badge) ![Verdi](https://img.shields.io/badge/SYNOPSYS%20VERDI-000000?style=for-the-badge&logoColor=white)  |
| **Embedded / SW** | ![C](https://img.shields.io/badge/C-FFD700?style=for-the-badge&logo=c&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Firmware (Bare-metal)](https://img.shields.io/badge/Firmware%20(Bare--metal)-03234C?style=for-the-badge) |
| **Board / Platform** | ![Basys3 FPGA](https://img.shields.io/badge/Basys3%20(FPGA)-87CEEB?style=for-the-badge&logo=amd&logoColor=white) ![Jetson Orin Nano](https://img.shields.io/badge/NVIDIA%20Jetson%20Orin%20Nano-76B900?style=for-the-badge&logo=nvidia&logoColor=white) ![STM32F411](https://img.shields.io/badge/STM32F411-03234C?style=for-the-badge&logo=stmicroelectronics&logoColor=white) ![MicroBlaze](https://img.shields.io/badge/MicroBlaze-1E90FF?style=for-the-badge&logo=amd&logoColor=white) |
| **Protocol** | ![APB](https://img.shields.io/badge/APB-50C878?style=for-the-badge) ![AXI4-Lite](https://img.shields.io/badge/AXI4--Lite-002B49?style=for-the-badge) ![I2C / SCCB](https://img.shields.io/badge/I2C%20%2F%20SCCB-412991?style=for-the-badge) ![SPI](https://img.shields.io/badge/SPI-556B2F?style=for-the-badge) ![UART](https://img.shields.io/badge/UART-FFD700?style=for-the-badge) |

---

### 📂 Featured Projects

| 프로젝트 | 설명 | 사용 기술 | Repo |
|---|---|---|---|
| **스마트 주차장**  | - Zybo Z7 보드와 Jetson Nano 보드를 활용한 스마트 주차장 시스템 구현 <br> - 차량 종류에 따른 빈자리 안내 및 실시간 위치 추적, 출차 시 요금 정산 기능 | SystemVerilog, UVM, C, Python, Zybo Z7 | [Link](https://github.com/sjy-kotmulhuji/smart_parking_lot_project) |
| **AXI4-Lite 기반 SoC 설계 및 UVM 검증** | - MicroBlaze CPU와 AXI4-Lite 프로토콜로 통신하는 SPI Master / I2C Master IP 설계 <br> - MicroBlaze 기반 SoC 시스템 구성 <br> - HAL 기반 Layered Architecture C Firmware 구현  | SystemVerilog, UVM, VCS, C | [Link](https://github.com/sjy-kotmulhuji/AXI4_Lite_SPI_I2C_Master) |
| **AMBA APB, RISC-V Multi Cycle CPU 기반 SoC 설계** | - RISC-V Multi Cycle CPU, APB Bus 설계 <br> - AMBA APB 프로토콜 기반 주변장치(BRAM, GPIO, FND, UART) 설계 <br> - C Firmware를 통한 Memory-mapped IO 제어 | Verilog HDL, SystemVerilog, Basys3 | [Link](https://github.com/sjy-kotmulhuji/RISC-V_multi_cycle_AMBA_APB_bus) |
| **SPI / I2C 통신 프로토콜 설계 및 UVM 검증** | - SPI, I2C 통신 프로토콜의 Master / Slave 모듈 RTL 설계 <br> - UVM 환경 구축을 통한 각 프로토콜 동작 기능 검증 <br> - FPGA 보드에 연결해 SPI Master / Slave 실제 동작 확인 | SystemVerilog, UVM | [Link](https://github.com/sjy-kotmulhuji/I2C_SPI_RTL_UVM) |
| **RISC-V Single Cycle CPU** | - RV32I ISA 기반 RISC-V 구조의 Single Cycle CPU 설계 및 Simulation <br> - C언어 코드를 활용한 Adder 예제 Code & Simulation 분석 | SystemVerilog, Basys3 | [Link](https://github.com/sjy-kotmulhuji/RISC-V_single_cycle_CPU) |
| **Multi-Functional Timer & Sensor System** | - FPGA 기반 UART 통신을 이용한 센서 및 시계 동작 시스템 <br> - Timer : Stopwatch, Watch 값 표시 <br> - Sensor : DHT11, SR04 센서를 통한 데이터 측정 및 표시 | SystemVerilog, Basys3 | [Link](https://github.com/sjy-kotmulhuji/Multi_Functional_Timer_Sensor_System) |
| **Rhythm Beat**  | - OV7670 + SCCB/I2C 색상 인식, VGA 출력 기반 리듬게임 구현 | SystemVerilog, Basys3, I2C | [Link](https://github.com/sjy-kotmulhuji/VGA_mini_rhythm_beat) |


---

### 🏆 Certifications & Awards
- 한국반도체아카데미 원장상 수상
- TOEIC Speaking AL (160점)
- 컴퓨터활용능력 1급
- 운전면허 2종 보통
---
