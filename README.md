![header](https://capsule-render.vercel.app/api?type=waving&color=000000&height=250&section=header&text=Robotics%20%C2%B7%20Embedded&fontSize=60&fontColor=ffffff&animation=fadeIn&desc=Device%20Integration%20%7C%20Field%20Testing&descAlignY=65&descAlign=50)

<div align="center">

## 👋 안녕하세요, 이석현입니다

**"로봇과 장치를 연결하고, 현장에서 예상과 다른 동작의 원인을 찾는 개발자"**

[![GitHub followers](https://img.shields.io/github/followers/LSH1218?style=social)](https://github.com/LSH1218)

</div>

---

### 🎯 About Me

- 👤 **이름**: 이석현 (Seokhyun Lee)
- 💼 **관심 직무**: Robotics / 임베디드 · 장치 연동
- 🎓 **학력**: 동양미래대학교 로봇공학과 졸업, 자동화공학과 전공심화 (GPA 4.2/4.5)
- 🔍 **관심 분야**: 로봇·장치 연동, 임베디드 제어, 현장 테스트와 문제 재현, 기록과 공유
- 📧 **Email**: sukhyun1218@gmail.com

---

### 🛠️ Tech Stack

<div align="center">

**프로젝트에서 사용**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white)
![C++](https://img.shields.io/badge/C%2FC++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**교과 실습**

![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![LabVIEW](https://img.shields.io/badge/LabVIEW-FFDB00?style=for-the-badge&logoColor=black)
![PLC](https://img.shields.io/badge/PLC%20%2F%20SCADA-555555?style=for-the-badge&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)

</div>

---

### 🚀 Projects

<details>
<summary><b>💬 모아말 — 학급회의 의견 정리 서비스</b> (2026.05 - 2026.10) | 개인 프로젝트</summary>

<br>

**교사 인터뷰에서 출발해, 학생 의견 수집 → AI 묶기 → 교사 승인 → 투표 → 기록으로 이어지는 서비스**

**🔧 사용 기술**
- Flutter, Firebase (Auth, Firestore 보안 규칙, Cloud Functions, Secret Manager, Hosting)
- OpenAI API (서버 프록시 경유)
- 구현에는 AI 개발 도구를 활용하고, 요구사항·우선순위 결정과 실기기 검증을 직접 담당

**✨ 주요 내용**
- 학생 화면 득표가 항상 0으로 표시되던 결함: 권한 규칙과 화면 집계 조건의 불일치를 찾아, 결과를 교실 앞 화면에서만 공개하는 방식으로 수정
- 재현 조건·원인·수정 내용·검증 결과를 결함 기록으로 관리
- 웹 체험 버전 배포: [moamal-1e601.web.app](https://moamal-1e601.web.app/) · 저장소: [moamal-flutter](https://github.com/LSH1218/moamal-flutter)

**💡 배운 점**
- 기능을 나눠 만들 때는 읽기·쓰기 권한과 기대 동작을 함께 맞춰야 함
- 기술보다 먼저 사용하는 사람의 업무 흐름을 이해해야 함
- 실제 수업에서의 효과 검증은 후속 과제로 남아 있음

</details>

<details>
<summary><b>💡 멀티모달 감정 인식 음악 추천 시스템 (MeloMatch)</b> (2024.03 - 2024.12) | 졸업작품 · 2인 팀</summary>

<br>

**얼굴·음성·텍스트로 사용자 상태를 분석해 음악을 추천하는 시스템**

**🔧 사용 기술**
- Python, OpenCV·DeepFace (나이·성별), PyQt5
- NLP: KcELECTRA (텍스트 감정 분석)
- SER: Wav2Vec2 (음성 감정 분석)

**✨ 담당 내용**
- 영상 기반 나이·성별 인식
- 텍스트·음성 감정 분석 모델 학습·적용, 데이터 불균형 조정
- 감정 라벨을 공통 범주로 맞추고 텍스트·음성 결과를 8:2로 가중 결합
- 분석 결과를 PyQt5 GUI에 통합 (음악 추천·AI 작곡은 팀원 담당)

**💡 배운 점**
- 여러 모델을 하나의 시스템으로 통합할 때 입력·출력 형식을 맞추는 일의 중요성
- 데이터의 품질과 균형이 결과의 신뢰성을 좌우함

</details>

<details>
<summary><b>🤖 반려동물 케어 로봇 (펫봇)</b> (2020.12 - 2021.05) | 3학년 캡스톤디자인</summary>

<br>

**혼자 있는 반려묘를 돌보는 Raspberry Pi 기반 로봇**

**🔧 사용 기술**
- Raspberry Pi, Python, OpenCV
- Bluetooth (RFCOMM), Flask 영상 스트리밍
- 앱인벤터 조종 앱

**✨ 주요 내용**
- 프로그램 담당 2명 중 1명으로 앱–로봇 통신과 주행 제어 담당
- 공개된 Bluetooth 서버·Flask 스트리밍 예제를 로봇 명령 체계에 맞게 수정·연결
- 앱에서 보낸 숫자 명령을 정지·자동주행·수동주행·방향 동작으로 연결
- OpenCV 얼굴 인식 결과로 접근·후진·탐색하는 자동 주행 모드
- 졸업 후 코드를 통신·비전·모터·주행 모드로 나눠 정리: [mungchi-capstone-3-1](https://github.com/LSH1218/mungchi-capstone-3-1)

**💡 배운 점**
- 각 예제가 따로 동작하는 것과, 앱·통신·카메라·모터가 하나의 흐름으로 맞물리는 것은 다름
- 기구·회로 작업이 지연될 때 작업 순서를 정리하고 역할을 조정해 통합을 이어감

</details>

<details>
<summary><b>🏎️ 기타 프로젝트</b></summary>

<br>

**라인 트레이싱 자율주행 씨름 로봇** (2020.09 - 2020.12) · [line-tracer-advanced-2-2](https://github.com/LSH1218/line-tracer-advanced-2-2)
- Arduino 센서 입력과 PWM 모터 제어, L298N 드라이버
- 실험실과 경기장의 조도 차이로 달라진 센서값을 측정해 임계값 조정
- **역할**: 소프트웨어 총괄, 팀원 이탈 후 기구·회로 문제 해결도 함께 담당

**서보/DC 모터 제어 로봇** (2020.03 - 2020.06)
- Arduino, C언어, HC-05 Bluetooth 모듈로 모바일 원격 제어
- 토크·기어비 검토로 팔 동작 개선

**사족보행 로봇** (2019.09 - 2019.12)
- 조립과 반복 주행 테스트
- 모터 토크 계산과 기어비 수정으로 직진 문제 해결

**주식 자동매매 알고리즘** (2023.09 - 2023.12) | 머신러닝 과목
- yfinance로 주가 데이터 수집, 이동평균선 교차 매매 신호와 백테스트 시각화

</details>

---

### 🌱 Tech Journey

> **문과 출신에서, 직접 만들고 확인하는 엔지니어로**

**2019.03 - 1학년: 첫 시작**
- 동양미래대학교 로봇공학과 입학 (3년제)
- 1학기 (03-06): **Python** 첫 접촉 → 레고 마인드스톰 로봇 제어
- 2학기 (09-12): **창의적공학설계** 과목 시작
  - 헤드셋 제작 (음향 원리 학습)
  - 사족보행 로봇 제작 (서보모터 구동 속도 경진)
- 첫 학기 학점 2.85 → 수능특강으로 수학/물리 기초 다시 공부

**2020.03 - 2학년: 아두이노 & 로봇 제어**
- 1학기 (03-06): **C 언어** 학습 시작
  - 서보/DC 모터 제어 로봇, 아두이노로 공 옮기기 대회 (블루투스 통신)
- 2학기 (09-12): **라인 트레이싱 자율주행 씨름 로봇**
  - 소프트웨어 총괄, 팀원 이탈 후 기구·회로 문제 해결까지 담당
  - 경기장 조도 차이에 따른 센서값 변화를 측정해 임계값 조정
- 2학기: **Python 재시작** → 라즈베리파이 학습

**2020.12 - 2021.05: 3학년 캡스톤디자인**
- **펫봇 (반려동물 케어 로봇)**
  - 프로그램 담당 2명 중 1명, 앱–로봇 통신과 주행 제어
  - Raspberry Pi + Python + OpenCV, 앱인벤터 조종 앱
- **사회복무요원 복무** (2021.07 - 2023.04)

**2023.09 - 복학**
- 머신러닝 수업: 주식 자동매매 알고리즘 프로젝트

**2024.02 - 로봇공학과 졸업 (전문학사)**

**2024.03 - 자동화공학과 전공심화과정**
- **멀티모달 감정 인식 음악 추천 시스템** 졸업작품 (2인 팀)
- STM32 통신·RTOS, PID·퍼지제어, PLC·SCADA 교과 실습
- **학점 4.2/4.5**

**2025.02 - 자동화공학과 졸업 (학사)** ✅

**2025.04 - 2026.02 - 진로 탐색**
- 의류 브랜드에서 검품·포장·팝업 준비 업무
- 몰입할 수 있는 일을 돌아보고 전공으로 돌아오기로 결정

**2026.05 - 2026.10 - 개인 프로젝트 모아말**
- 교사 인터뷰부터 개발·실기기 검증·웹 배포까지 혼자 진행

**일하는 방식**
- ✅ 모르는 지점을 찾아 기초부터 채우기 (첫 학기 2.85 → 전공심화 4.2)
- ✅ 원인 후보를 하나씩 확인하기 (센서 단독 테스트 → 환경 측정 → 기준값 조정)
- ✅ 현장에서 직접 확인하기 (실험실이 아닌 경기장·실기기에서 검증)
- ✅ 내가 없어도 점검할 수 있게 남기기 (결함 기록, 점검 방법 공유)

---

### 💼 Interest Areas

<table>
<tr>
<td align="center" width="33%">

**🤖 로봇·장치 연동**

앱·통신·센서·모터를<br>
하나의 흐름으로

</td>
<td align="center" width="33%">

**🔧 현장 테스트**

예상과 다른 동작의<br>
원인 재현하고 좁히기

</td>
<td align="center" width="33%">

**📝 기록과 공유**

다음 사람이 이어받을<br>
점검 방법 남기기

</td>
</tr>
</table>

---

### 📞 Contact

<p align="center">
<a href="mailto:sukhyun1218@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/LSH1218"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

<div align="center">

**"배우고, 만들고, 개선하며 성장합니다"**

![footer](https://capsule-render.vercel.app/api?type=waving&color=000000&height=120&section=footer)

</div>
