# 🏎️ NEON DRIFT: UNDERGROUND APEX
> **2D Top-Down Physics Racing & Tuning Career RPG**  
> *Gran Turismo*, *Need for Speed*, *GeneRally*의 깊이 있는 물리와 머신 튜닝 감성을 브라우저 단 하나의 파일로 완성한 탑다운 레이싱 게임.

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-00f3ff?style=for-the-badge&logo=github)](https://jeiel85.github.io/neon-drift-apex/)
[![Vanilla JS](https://img.shields.io/badge/Pure-Vanilla%20JS%20%26%20Canvas%202D-ff0055?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Web Audio API](https://img.shields.io/badge/Audio-Procedural%20Web%20Audio-ffe600?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Zero Dependency](https://img.shields.io/badge/Dependency-0%20(Single%20HTML)-00ff88?style=for-the-badge)](#)

---

## 🌆 세계관 및 테마 (World & Theme)
네온사인이 번쩍이고 비에 젖은 아스팔트가 반사되는 야간 사이버 시티의 지하 언더그라운드 레이싱 리그.  
무명의 신인 드라이버로 시작하여, 12개 서킷을 제패하고 6종의 머신을 최고 등급으로 튜닝해 **그랜드 마스터 리그**의 전설로 등극하세요!

---

## 🎮 라이브 데모 (Live Demo)
👉 **[지금 브라우저에서 즉시 플레이하기](https://jeiel85.github.io/neon-drift-apex/)**  
*(별도 설치나 외부 라이브러리 로딩 없이 모바일 및 데스크톱 브라우저에서 즉시 실행됩니다)*

---

## 🕹️ 조작법 (Controls)

### 💻 키보드 (Desktop)
| 조작키 | 동작 설명 |
| :---: | :--- |
| **W** / **▲** | 스로틀 가속 (Accelerate) |
| **S** / **▼** | 풋브레이크 / 후진 (Brake & Reverse) |
| **A** / **D** / **◀** / **▶** | 전륜 조향 스티어링 (Steer Left / Right) |
| **SPACE** | **핸드브레이크 파워 드리프트 (Handbrake Power Slide)** |
| **SHIFT** | **NOS 니트로 부스터 (Nitrous Boost)** |
| **ESC** | 레이스 일시정지 (Pause Menu) |

### 📱 모바일 터치 컨트롤 (Mobile / Tablet)
- 화면 좌측: **좌/우 방향 가상 버튼**
- 화면 우측: **가속(▲), 브레이크(■), 파워 드리프트(DRIFT)**

---

## ⚡ 핵심 시스템 및 특징 (Key Features)

### 1. 2D 타이어 물리 & 드리프트 시뮬레이션 (Impulse Tire Friction)
- **Bicycle Model & Pacejka 비선형 타이어 마찰**: 차체 질량, 휠베이스, 관성 모멘트, 조향각 및 횡방향 슬립 속도 계산
- **파워 드리프트 & 카운터스티어**: 스페이스바(핸드브레이크)로 후륜 트랙션을 차단하고, 반대 방향 스티어링으로 미끄러지는 궤적을 제어
- **실시간 드리프트 콤보 & NOS 충전**: 슬립 각도와 속도에 비례해 점수와 배율이 상승하며, 드리프트 유지 시 니트로 부스터 자동 충전
- **영구 스키드 마크 & 파티클 연출**: 노면에 영구적으로 새겨지는 4륜 타이어 스키드 마크, 드리프트 연기, 가드레일 충돌 스파크, NOS 백파이어 불꽃

### 2. 4단계 커리어 리그 & 12개 서킷 (Career Progression)
- **1. 루키 컵 (Rookie Cup)**: Neon Docks, Industrial Alley, Harbor Sprint
- **2. 클럽맨 컵 (Clubman Cup)**: Riverside Loop, Expressway Junction, Chinatown Chicanes
- **3. 나이트 스트리트 (Night Street)**: Neo Shinjuku Strip, Cyber Tunnel Run, Midnight Skyline
- **4. 그랜드 마스터 (Grand Master)**: Apex International Ring, Devil's Hairpin Pass, Underground Grand Finale
- **지능형 AI 3대 라이벌**: 웨이포인트 추종, 코너 전 감속 및 드리프트, 충돌 회피 기동
- **슬립스트림(Slipstream) 추월 시스템**: 선행 차량 후류에 진입 시 공기저항 감소 및 가속 부스트 발동

### 3. 차고지(Garage) & 6대 하드웨어 튜닝 시스템
- **6종 머신 라인업**:
  - `AE-Sprinter` (경량 입문 해치백, 민첩한 회두성)
  - `Silvia-K2` (스트리트 쿠페, 정통 FR 드리프트 머신)
  - `Muscle-V8 Thunder` (클래식 머슬, 폭발적인 V8 토크와 파워 오버스티어)
  - `Rotary-Apex RX` (로터리 스포츠카, 9,000 RPM 초고회전 밸런스)
  - `Shadow-R AWD` (튜너 AWD 레전드, 4륜 로켓 트랙션)
  - `Phantom-GT Midship` (미드십 트윈터보 하이퍼카, 한계 그립의 정점)
- **6대 하드웨어 튜닝 (각 5단계 레벨업)**:
  - **Engine (엔진 블록 & ECU)**: 최고속도 및 고회전 출력 향상
  - **Turbo (트윈 터보차저)**: 가속 토크 증대 및 부스트 스풀 단축
  - **Tires (컴파운드 타이어 & 서스펜션)**: 코너링 횡그립 한계 상향 및 드리프트 안정성
  - **Brakes (카본 세라믹 브레이크)**: 제동력 및 핸드브레이크 파워락 반응성 개선
  - **Chassis (경량 카본 섀시)**: 총 중량 감소 $\rightarrow$ 가속 및 선회 민첩성 극대화
  - **NOS (액화 니트로 키트)**: 부스터 저장 용량 및 분사 압력 강화
- **네온 컬러 커스터마이징**: 사이버 핑크, 일렉트릭 블루, 네온 옐로우 등 8종 도색 지원

### 4. 1/4마일(400m) 드래그 레이스 (Drag Strip)
- 전용 타코미터 계기판 및 RPM 바늘 애니메이션
- 그린존(Green Shift Zone) 수동 기어 변속(스페이스/버튼) 타이밍 판정 (*Perfect, Good, Early, Late*)
- 0-100km/h(제로백) 및 400m 주파 시간 계측 및 승리 상금 수여

### 5. 스폰서 의뢰 계약 (Bounties)
- 스모크 킹 (단일 레이스 드리프트 3,500점 이상)
- 고스트 드라이버 (가드레일 충돌 3회 이하 클린 레이스 우승)
- 쿼터마일 데몬 (드래그 레이스 11.5초 언더)
- 언더그라운드 레전드 (그랜드 마스터 서킷 우승)

### 6. Web Audio API 절차적 사운드 합성 (Procedural Audio)
- 외부 사운드 파일(mp3/wav) 0개! 순수 수학적 파형 합성:
  - **엔진 배기음**: 실시간 RPM 및 스로틀에 연동되는 톱니파 + 비대칭 왜곡(Distortion) + 저역 필터
  - **타이어 스킬(Skid)**: 타이어 슬립 속도에 비례하는 대역통과 필터 화이트 노이즈
  - **NOS 제트 기류 사운드**: 고주파 노이즈 스위프
  - **충돌 임팩트 사운드**: 메탈릭 임팩트 왜곡파
  - **UI 사운드**: 네온 사이버펑크 톤 비프음

### 7. 영속성 및 자동 저장 (LocalStorage)
- 보유 크레딧, 보유 차량, 장착 튜닝 파츠, 서킷별 트로피/별점, 베스트 랩타임 100% 자동 백업.

---

## 🛠️ 기술 스택 (Tech Stack)
- **Language**: Vanilla JavaScript (ES6+)
- **Graphics**: HTML5 Canvas 2D API (Dual-buffer & Offscreen Surface)
- **Audio Engine**: Web Audio API (OscillatorNode, BiquadFilterNode, WaveShaperNode)
- **Styling**: Modern CSS3 (Glassmorphism, Flexbox/Grid, Responsive)
- **Storage**: Web Storage API (LocalStorage)

---

## 📜 라이선스 (License)
MIT License. 자유롭게 즐기시고 커스터마이징해 보세요!
