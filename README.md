# 한규영 | AI Engineer

**인공지능융합학부 4학년 · 더그리트(The Greet) 플랫폼팀 인턴**  
Computer Vision · Backend · Cloud에 관심이 많습니다

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**AI / ML**
`Python` `PyTorch` `YOLOv8` `ONNX Runtime` `MobileNetV3` `UNet3+`
Computer Vision · Rule-based + DL Hybrid 판별 · Active Learning · Segmentation

**Backend**
`FastAPI` `asyncio` `TCP/FTP 소켓 통신`

**Cloud**
`AWS` (Amazon Connect, Lex V2, Lambda, Bedrock, DynamoDB, IoT Core)

**Database**
`MySQL` `AWS RDS`

**Others**
`iRAYPLE EasyVS` `Windows GDI API` `PyInstaller` `C# WinForms`

---

## 📂 Projects

### 🥤 [Reverse Vending Machine Vision Pipeline](https://github.com/GY-H08/reverse-vending-vision-pipeline)
일회용컵 무인 반납기 컴퓨터 비전 판별 시스템. 카메라 구성부터 통신 프로토콜, 판정 알고리즘, 보조 딥러닝 모델까지 설계 단계부터 단독 구축.
- 상단/측면 듀얼 카메라, EasyVS 9-Class 판별 구조 설계 (14→9 축소로 오거부 문제 해결)
- 투명 액체(물) 감지를 위한 ripple pulse 기법 직접 고안 — 회전판을 짧게 반복 구동시켜 인위적 파동 생성
- 바코드 인식 ROI 3분할(중앙+좌+우)로 컵 위치 편차 문제 해결, 이중 바코드(훼손 컵) 감지 로직 구현
- MobileNetV3-Small 기반 ONNX 2차 검증 모델 직접 데이터 수집·학습·연동
- KTC 인증 시험 FAIL(90%대) → 이물질 전유형 100% 거부까지 개선
- `Python` `FastAPI` `asyncio` `ONNX Runtime` `TCP Socket` `iRAYPLE EasyVS`

### 🔬 [Defect Segmentation Vision System](https://github.com/GY-H08/defect-segmentation-vision-system)
제조 현장 표면 결함 검사를 위한 세그멘테이션 시스템.
- UNet3+ 기반 커스텀 아키텍처 실험 (UNet3+MSCA+SWA, UNet3+ASPP+SWA 등 반복 실험 및 성능 비교)
- Hard Object(광학 반사로 인한 오탐) 자동 threshold 최적화 스크립트 구현
- 정량적 실험 리포트 작성 및 버전별 성능 비교 분석
- `Python` `PyTorch` `UNet3+` `Image Segmentation`

### 🚗 [Vehicle Damage Detection](https://github.com/GY-H08/vehicle-damage-detection)
YOLOv8 기반 2-stage 차량 손상 탐지 파이프라인.
- 원본 이미지 약 56만 장 → 정제 후 약 13만 장으로 전처리, 클래스 불균형 해결
- Part(부위) 모델 mAP50 약 80%, Damage(손상) 모델 mAP50 약 40.8% 달성
- Active Learning 기반 데이터 선별 전략 적용
- `Python` `YOLOv8` `Active Learning`

### 📞 AWS ARS 자동화 시스템
반납기 이용 고객을 위한 음성 기반 CS 자동화 시스템.
- Amazon Connect + Lex V2 + Lambda + Bedrock + DynamoDB 연동 설계
- 고객 조회 플로우(GSI 기반) 및 시나리오 설계
- `AWS Connect` `Lex V2` `Lambda` `Bedrock` `DynamoDB`

### 🏷️ QR 라벨 자동 출력 시스템
반납기 현장에서 사용하는 QR 라벨 출력 프로그램.
- GDI 기반(폼텍 라벨지) / TSPL 기반(전용 프린터) 이중 출력 방식 지원
- PC별 site/module 설정을 config.json으로 관리, PyInstaller EXE로 배포
- `Python` `PyQt5` `Windows GDI API` `PyInstaller`

### 🥤 [Cup Return Vision System](https://github.com/GY-H08/cup-return-vision-system)
반납기 컵 검사 AI 시스템 초기 버전 (reverse-vending-vision-pipeline의 이전 단계).
- `Python` `Computer Vision`

### 💪 SmartLift — 운동 기록 관리 시스템
C# WinForms + MySQL 기반 데스크톱 운동 트래킹 애플리케이션.
- `C#` `WinForms` `MySQL`

---

## 🎓 Education & Coursework
- 삼육대학교 인공지능융합학부 4학년
- 신경모방 컴퓨팅(Neuromorphic Computing), 클라우드 컴퓨팅 등 관련 교과 이수

---

## 📬 Contact

Email: pillhy12@naver.com
