# SayUP 프로젝트 소개

### 📝 개요
SayUP은 AI 기반 한국어 학습 애플리케이션입니다. 
사용자의 음성을 분석하여 맞춤형 피드백을 제공함으로써, 보다 자연스럽고 자신감 있는 언어 학습을 돕습니다.

<br>

### 🏗 시스템 아키텍처
<br>

![Group 37270](https://github.com/user-attachments/assets/1eb6c289-c42f-4c02-994b-f437265413bc)

<br>

### 💾 ERD
https://www.erdcloud.com/d/wcmG3wt34kxKD6zxu

<br>


### 💻 Tech Stack</h4>
**Frontend**
<p align="left">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=Flutter&logoColor=white"/> 
</p>

**Backend**
<p align="left">
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=Spring-Boot&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"/> 
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white"/> 
</p>

**Database**
<p align="left">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"/> 
</p>

**DevOps**
<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"/> 
</p>

<br>

### 🚀 주요 기능
**Voice Recorder**
- **음성 분석 및 합성**: OpenVoice를 활용하여 사용자의 음성을 벡터화하고, 입력한 문장을 자연스럽게 수정하여 발음 교정을 지원합니다.

**Free Talking**
- **AI 챗봇 대화 학습**: OpenAI ChatGPT API를 활용하여 자연스러운 한국어 대화를 제공합니다.
- **맞춤형 음성 피드백**: 사용자의 음성을 반영한 음성 파일을 제공하며, 향후 발음 평가 기능이 추가될 예정입니다.

**발음 평가 시스템**
- **음소 단위 분석**: MFCC 및 DTW 알고리즘을 사용하여 표준 발음과 비교 평가합니다.
- **유사도 분석**: 음성을 텍스트로 변환 후, DTW 및 LCS 알고리즘을 활용하여 발음 유사도를 점수화합니다.
- **맞춤형 피드백 제공**: 발음 오류를 분석하여 효과적인 교정 방법을 제시합니다.

<br>

### 🎥 입 모양 분석 (개발 중)
**실시간 입술 분석**
- **MediaPipe 활용**: 실시간으로 입술 랜드마크를 추출하여 발음 교정에 활용합니다.
- **AI 기반 립리딩 모델**: MobileNet과 LSTM을 결합하여 입술 움직임을 분석하고 발음 평가의 정확도를 높입니다.

<br>

### 🔮 향후 개발 기능
**상황극 기능**
- 특정 시나리오 기반 대화 연습을 통해 실전 감각을 향상합니다.

**문맥 분석**
- 표정 인식 기술을 활용하여 감정에 맞는 적절한 반응을 학습할 수 있도록 지원합니다.

**친구 추가 기능**
- 승인된 친구들과 대화하며, 음성 데이터를 활용해 더욱 실감 나는 대화 경험을 제공합니다.

---

사용자가 더욱 자연스럽고 자신감 있게 말할 수 있도록, 지속적인 연구와 개발을 이어나가겠습니다! ✨

