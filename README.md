# 🎨 Good LUT Maker (Good LUT 메이커)

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![PyQt6](https://img.shields.io/badge/PyQt-6-green.svg)](https://www.riverbankcomputing.com/software/pyqt/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Good LUT Maker**는 사진과 영상 보정 전문가들을 위한 강력하고 직관적인 **3D LUT 제작 도구**입니다. HALD 패턴 기술을 기반으로 하여, 이미지 편집 프로그램에서 작업한 색감을 그대로 `.cube` 파일로 추출할 수 있습니다.

## 📥 다운로드 (Download)

최신 버전의 인스톨러(.exe)는 **[GitHub Releases](https://github.com/marushin/good-lut-maker/releases)** 페이지에서 다운로드할 수 있습니다.

## ✨ 주요 기능 (Key Features)

*   **실시간 프리뷰**: 각종 색보정 슬라이더(밝기, 대비, 채도, 색조 등)를 조절하며 실시간으로 결과를 확인하세요.
*   **3D LUT 추출**: HALD 이미지를 활용하여 작업한 색감을 업계 표준인 17, 33, 64, 65 사이즈의 3D LUT  `.cube` 파일로 저장할 수 있습니다.
*   **영상 지원**: 이미지뿐만 아니라 영상(.mp4, .mov 등)에도 저장한 LUT를 즉시 적용하고 미리볼 수 있습니다.
*   **모던한 UI**: 세련된 다크 모드와 직관적인 레이아웃으로 작업 효율을 극대화했습니다.


## 🛠 사용된 기술 (Tech Stack)

*   **Language**: Python 3.10+
*   **GUI**: PyQt6
*   **Image Processing**: NumPy, Pillow (PIL), colour-science
*   **Video Processing**: FFmpeg (via moviepy/ffmpeg-python)
*   **Build Tool**: PyInstaller, Inno Setup


### 👨‍💻 기여하기
버그 제보나 기능 제안은 언제나 환영합니다! Issue를 남겨주시거나 Pull Request를 보내주세요.

**"Good Luck with your Good LUT!"**
