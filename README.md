# 👨‍💻 장시영 | 임베디드 시스템 및 스마트시티 기술 개발자  
**지능형 계측, 펌웨어 커스터마이징, 공공 시스템 최적화의 실전 경험을 바탕으로, 현장에서 바로 쓰이는 기술을 개발합니다.**

---

## 🧑‍🔬 소개

임베디드 시스템 및 스마트시티 기반 지능형 계측 기술을 연구하는 개발자입니다.  
**펌웨어 커스터마이징**, **AI 기반 유량 분석**, **홍수예측 시스템 구축**, **공공기관 시스템 최적화** 등의 프로젝트에 참여하며  
**현장 요구를 반영한 실용적 기술**을 설계하고 **성과 중심의 시스템 혁신**을 이끌고 있습니다.

---

## 🛠️ 기술 스택

- **프로그래밍 언어:** Python, C/C++, Java, JavaScript, Bash  
- **임베디드 시스템:** Embedded Linux, STM32, RS485/Modbus, LVGL, PoE 기반 통신 설계  
- **프론트엔드/UI 개발:** PyQt, Qt Designer, PyQtGraph, HTML/CSS  
- **오디오/비디오 처리:** GStreamer, FFmpeg, OpenCV  
- **클라우드/인프라:** Google Cloud Platform (GCP), GitHub Actions, Linux 서버 운영 및 CI/CD 구축  

---

## 🚀 주요 프로젝트 및 기여

### 🖥️ EdgeTX 한글 펌웨어 PR [#6118](https://github.com/EdgeTX/edgetx/pull/6118), [#6220](https://github.com/EdgeTX/edgetx/pull/6220) – ✅ 머지 완료  
TX16S 조종기 및 다양한 EdgeTX 장비에 **완전한 한국어 UI 지원**을 구현했습니다.

- NanumBarunpenR/B 폰트를 경량화하여 펌웨어 최적화  
- fonts.cpp, make_fonts.sh, lv_font_conv, ko.h 등 폰트 처리 파이프라인 전면 개선  
- Companion에 기존 영어 `.ts`를 기반으로 생성된 Korean 항목에 완전한 한글 번역 적용 
- 전체 메뉴 및 설정 항목에 자연스러운 한국어 표현 제공
- 2.11.1 버전부터 `View > Language > 한국어` 메뉴로 활성화 가능
- 실기기(TX16S) 환경에서 한국어 UI 렌더링 완성  
- 리뷰 피드백을 반영한 최종 번역 품질 개선 및 반영 완료
- 빌드 자동화 스크립트 통과 및 최적화 검증 완료  

### 🎙️ EdgeTX 한국어 음성팩 PR [#143](https://github.com/EdgeTX/edgetx-sdcard-sounds/pull/143) – ✅ 머지 완료  
EdgeTX v2.9 SD 카드에 공식 포함될 **고음질 한국어 음성팩**을 개발했습니다.

- Google Cloud TTS API 기반 자연스러운 한국어 음성 생성  
- sounds/ko, ko-KR.csv, ko-KR_scripts.csv 체계 구성  
- build-checks.py 자동 검증 스크립트 통과  
- 확장성과 유지보수를 고려한 구조 설계  

### 🎨 한국 전통 테마 디자인 – ✅ 공식 머지 완료 [링크](https://github.com/EdgeTX/themes)  
한국 전통 미학을 반영한 UI 테마 3종을 공식 등록했습니다.

- **Hanji**: 전통 한지 질감을 활용한 테마제작
- **Hunminjeongeum**: 훈민정음 서체 기반 고전 감성 테마제작
- **Korean Royal Garden**: 창경궁 후원의 정갈한 미학을 적용한 테마제작
- 다양한 해상도(320x240, 480x320) 지원  
- EdgeTX Theme Manager에 정식 등록 완료  
<img width="748" height="193" alt="image" src="https://github.com/user-attachments/assets/5f6a178b-4db5-42a7-9299-1b904fdb50f2" />
<img width="754" height="188" alt="image" src="https://github.com/user-attachments/assets/eebd3b25-4a9b-45d2-9704-19237810064e" />
<img width="743" height="189" alt="image" src="https://github.com/user-attachments/assets/7acbe428-632b-4e9c-a006-198acb04c506" />

---
### 🧠 *현주메모* (기억 상기 앱)
<img width="1073" height="615" alt="image" src="https://github.com/user-attachments/assets/654ff799-1035-4bf1-9644-cf1b84099af3" />

아내의 잦은 건망증을 계기로,  
**“기억을 요구하지 않고 자동으로 상기시켜주는 앱”**을 직접 기획·개발했습니다.

**스마트폰을 여는 순간 짧게 노출되고 빠르게 사라지는 UX**를 통해  
저절로 기억되는 것을 목표로 했습니다.

**핵심 특징**
- 스마트폰 **화면 활성화 시 자동 노출**
- 0.1~2초 사이의 **짧은 노출 후 자동 사라짐**
- 사용자의 인지 부담을 최소화한 리마인드 방식
- “기억하라”가 아닌 **“잊기 어렵게 만드는 구조”**

**주요 기능**
- 노출 시간 및 빈도 사용자 설정  
- 텍스트 + 이미지 기반 메모 항목 관리  
- 항목별 배경색 커스터마이징을 통한 시각적 기억 강화  
- 즉시 추가 가능한 경량 입력 UI  

> 기술보다 UX 타이밍과 사용자 행동 변화를 우선한 프로젝트로,  
> 일상의 문제를 구조적으로 해결하는 접근을 경험했습니다.


---
## 📈 오픈소스 활동 요약

| 분야                           | 상세 내용                                                      |
|------------------------------|---------------------------------------------------------------|
| 펌웨어 로컬라이제이션          | EdgeTX 한글화, 폰트 통합, Companion UI 한글 지원              |
| 음성팩 개발                   | 한국어 TTS 음성팩 제작 및 최적화 PR 기여                       |
| 테마 디자인                   | 한국적 감성의 UI 테마 3종 공식 등록 및 배포                    |
| 자동화 및 최적화              | 폰트 빌드, 음성 검증 스크립트 자동화, 최적화 구조 구축        |

---

## 🌏 경력 및 주요 성과

- 🎥 **AI 기반 영상 유량계 시스템 개발**  
  - OpenCV 기반 실시간 영상 분석 + RS485 장비 제어 통합  
- 🧠 **소하천 홍수예측 AI 시스템 구축**  
  - IoT 센서 융합 + 머신러닝 + 조기경보 시스템 설계  
- 🚦 **스마트시티 기반 UTIS 시스템 상용화**  
  - 도시 교통 데이터 수집·분석 시스템 개발  
- ⚖️ **대법원 전자소송 시스템 리팩토링**  
  - 수십만 사용자 대상 안정성과 확장성 개선  

---

## 📫 연락처

- 🐙 GitHub: [@siyeongjang](https://github.com/siyeongjang)  
- 📧 Email: siyeongj08@gmail.com  
- ✍️ Blog: (Coming soon)

---
