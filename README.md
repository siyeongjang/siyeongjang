## 🚀 주요 프로젝트 및 기여 (Projects and Contributions)

### 🖥️ [EdgeTX 한글 펌웨어 PR #6118](https://github.com/EdgeTX/edgetx/pull/6118) – ✅ 머지 완료 (Merged)
> TX16S 조종기 및 다양한 EdgeTX 장비에 **완전한 한국어 UI 지원**을 구현했습니다.  
> Provided full Korean UI support for TX16S transmitters and various EdgeTX devices.

- NanumBarunpenR/B 폰트를 경량화하여 펌웨어 최적화
- `fonts.cpp`, `make_fonts.sh`, `lv_font_conv`, `ko.h` 등 폰트 처리 파이프라인 전면 개선
- Companion 소프트웨어 및 실기기(TX16S) 환경에서 한국어 UI 렌더링 완성
- 빌드 자동화 스크립트 통과 및 최적화 검증 완료
-  
- Integrated lightweight NanumBarunpenR/B fonts optimized for firmware
- Enhanced the font processing pipeline (`fonts.cpp`, `make_fonts.sh`, `lv_font_conv`, `ko.h`)
- Completed Korean UI rendering validation on Companion software and real TX16S devices
- Successfully passed automated build verification and optimization checks

---

### 🎙️ [EdgeTX 한국어 음성팩 PR #143](https://github.com/EdgeTX/edgetx-sdcard-sounds/pull/143) – ✅ 머지 완료 (Merged)
> EdgeTX v2.9 SD 카드에 공식 포함될 한국어 음성팩 개발  
> Official Korean voice pack included in EdgeTX v2.9 SD card.

- Google Cloud TTS API를 사용해 고음질 한국어 음성 생성
- `sounds/ko`, `ko-KR.csv`, `ko-KR_scripts.csv` 체계적 구성
- `build-checks.py` 자동 검증 스크립트 통과
- 향후 유지보수를 고려한 확장 가능한 설계
-  
- Created natural Korean voices using Google Cloud TTS API
- Built structured `sounds/ko`, `ko-KR.csv`, and `ko-KR_scripts.csv`
- Passed `build-checks.py` validation with full compatibility
- Designed for scalable future maintenance

---

### 🎨 [한국 전통 테마 디자인 (공식 머지 완료)](https://github.com/EdgeTX/themes)
> 한국 전통 미학을 살린 테마 3종을 EdgeTX 공식 테마 저장소에 병합  
> Contributed three themes inspired by Korean aesthetics to the official repository.

- **Secret Garden KR**: 창경궁 비원의 고요하고 정갈한 아름다움을 현대적으로 재해석
- **Hanji**: 전통 한지 질감을 활용한 고급스러운 UI 디자인
- **Hunminjeongeum**: 훈민정음 서체를 모티브로 한 고전 감성 테마
- 다양한 해상도(`320x240`, `480x320`) 지원
- EdgeTX Theme Manager에 정식 등록 완료
-  
- **Secret Garden KR**: A serene reimagining of the Changgyeonggung Secret Garden
- **Hanji**: A premium UI design featuring traditional Hanji paper textures
- **Hunminjeongeum**: A theme evoking the beauty of ancient Korean script
- Supports multiple resolutions (`320x240`, `480x320`)
- Officially registered in EdgeTX Theme Manager
