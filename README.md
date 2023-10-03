<!-- 어떤 연구분야에서 어떻게 성과를 냈는지, 내 역량의 범위는 어떻게 되는지에 집중하여 간략하게 작성하는 것이 중요합니다. -->
<!-- 회사는 여러분들이 회사에서 진행 중인 또는 진행할 프로젝트에 기여를 할 수 있는 역량을 가진 사람인가를 궁금해합니다. 
     때문에 여러분들의 연구나 프로젝트를 상위 레벨에서 쉽게 설명하고 어떤 역량을 키웠으며 내가 가진 역량으로 어떤 산업과 프로젝트에 적용할 수 있는지를 구체적으로 보여주는 것이 중요합니다. -->
<!-- AI기술에 대한 경험기술서 (직접 활용해 본 AI기술들에 대한 구축 경험과 시행착오가 담긴 기술서)
     예시)
          어떠한 목표를 달성하기 위하여, AI 기술 중 Voice Conversion을 활용 하기로 하였음
          이 과정에서 어떠한 모델을 선정 하였고 Raw데이터를 이러한 방식으로 준비하여 파인튜닝을 하였음. 
          그 과정에서 이러한 시행착오를 겪었음. 결과 모델들 중 이러한 기준으로 최종 모델을 선정 함. -->



# 📢 프로젝트 소개
### 주제 선정 이유
- 인공지능 스피커를 활용한 활동이 유아의 표현언어 능력에 영향을 미침
- 아동의 경우 더 적극적으로 인공지능 스피커와 상호작용하며, 인공지능 스피커 시장에서도 주요 타겟층으로 여겨짐
- "시크릿 쥬쥬 셀카폰" 장난감이 판매중이지만 녹화된 음성을 계속 되풀이하는 한계가 있음
- 아동들에게 좋아하는 캐릭터와 대화를 나누는 듯한 경험을 선사할 수 있음
- 아동 AI교육 도구로써 사용할 수 있음
- 아동 표현 언어 발달에 도움을 줄 수 있음

<br>

### 주요 기능
- STT
     - 사용자로 부터 음성을 입력 받아 생성한 음성파일을 자연어 문자열로 변환
     - 자연어 문자열은 챗봇 및 감정분석에 활용하기 위해 활용
- Chatbot
     - "치링치링 시크릿 쥬쥬"를 연기하는 챗봇
     - 해당 캐릭터의 설정을 그대로 연기
     - 어린이와의 대화에 알맞은 답변을 출력
- Sentiment Analysis
     - "치링치링 시크릿 쥬쥬"의 답변에서 감성분석을 통해 감정 추출
     - 답변과 함께 상황에 알맞은 표정을 짓도록 함
- WAV to Lipsync
     - "치링치링 시크릿 쥬쥬"의 입모양을 자연스럽게 바꿔주기 위함
- Voice Cloning
     - "치링치링 시크릿 쥬쥬"의 목소리로 답변을 출력

<br>

### 사용 기술
[![Python Badge](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=for-the-badge)](https://www.python.org/)
[![Openai](https://img.shields.io/badge/openai_gpt4-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![Langchain](https://img.shields.io/badge/%F0%9F%A6%9C%F0%9F%94%97langchain-fff?style=for-the-badge)](https://www.langchain.com/)
[![Flask Badge](https://img.shields.io/badge/Flask-000?logo=flask&logoColor=fff&style=for-the-badge)](https://flask.palletsprojects.com/en/3.0.x/)
[![ngrok Badge](https://img.shields.io/badge/ngrok-1F1E37?logo=ngrok&logoColor=fff&style=for-the-badge)](https://ngrok.com/)

[![Static Badge](https://img.shields.io/badge/KoBERT-gray?style=for-the-badge)](https://sktelecom.github.io/project/kobert/)
[![Static Badge](https://img.shields.io/badge/VITS-gray?style=for-the-badge)](https://github.com/jaywalnut310/vits)
[![Static Badge](https://img.shields.io/badge/RVC-gray?style=for-the-badge)](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)
[![Static Badge](https://img.shields.io/badge/Wav2Lip-gray?style=for-the-badge)](https://github.com/Rudrabha/Wav2Lip)

| Tech | Purpose |
| --- | --- |
| Openai GPT-4 API | 프롬프트 튜닝을 통해 특정 캐릭터의 설정을 연기하고 사용자엑 절적한 대답을 하는 역할 |
| Langchain | LLM을 제어하고 대화내역을 기억하도록 하기 위해 사용 |
| Flask | 서비스에 필요한 수많은 서버들을 구축하고 통신하기 위해 사용 |
| KoBERT | 감성분석을 위해 사용 |
| ngrok | 고정 IP를 부여하기 위해 사용 |
| VITS | TTS를 위해 사용 |
| RVC | 목소리 변조를 위해 사용 |
| Wav2Lip | 입모양을 자연스럽게 생성하기 위해 사용 |


<br><br>
# 👥 팀원 소개 및 역할
### [김우정]
- 역할: 
  - ㅁ

### [김해니]
- 역할:
  - ㅁ

### [이승현] << Me!
- 역할:
  - 

### [정민교]
- 역할: 
  - ㅁ


<br><br>
# 📅 프로젝트 진행과정
### 일정관리
![스크린샷 2023-10-04 012941](https://github.com/Blessian/JUJUbot/assets/74029539/a5eb57c5-f624-4a43-a417-2f31546b0b6b)
- 간트차트 작성
 

### 데이터 소개
- 데이터 출처 및 수집 방법: 
- 데이터 특성: 데이터의 종류, 형식, 크기 등
- 데이터 전처리: 데이터를 모델 학습에 적합한 형태로 가공한 과정과 사용한 도구, 기술에 대한 설명
- 

<br>

### 모델 선정과 구현
최종적으로 선택한 모델과 최종 선택한 이유, 모델의 구조와 구현 방법 설명

<br>

### 진행과정 (시행착오)
시간 순서에 따른 진행과정 나열, 발생한 어려움과 시행착오, 그리고 해결 방법에 대한 설명


<br><br>
# 📊  결과
### 최종 모델 성능과 결과 해석
모델의 성능 지표와 결과 해석

<br>

### 프로젝트에서 얻은 교훈과 인사이트
프로젝트를 통해 얻은 교훈과 향후 프로젝트에 적용할 인사이트


<br><br>
# 📝 향후 계획
### 자기평가
프로젝트에서 본인이 수행한 역할과 기술 습득 정도에 대한 자기평가

<br>

### 향후 계획
AI 기술에 대한 추가 학습 계획이나 심화 프로젝트에 대한 기획 소개


<br><br>
# 🔗 참고 자료
### 사용한 논문 및 자료
- [인공지능 스피커를 활용한 활동이 유아의 언어능력에 미치는 영향](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002770401)
- [인공지능 스피커와 아동들의 상호작용 :유형별 성공/실패 사례 도출을 위한 현장 연구](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002611329)
- [치링치링 시크릿 쥬쥬](https://www.youtube.com/@SecretJouju)
- [KoBERT](https://sktelecom.github.io/project/kobert/)
- [VITS](https://github.com/jaywalnut310/vits)
- [RVC](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)
- [Wav2Lip](https://github.com/Rudrabha/Wav2Lip)


<!-- 
# JUJUbot  
  
어린이 대화 친구 AI 프로젝트  
사용자 보이스 대화를 입력 받아 캐릭터가 대답하는 영상을 송출한다.  
  
## Branch   
   
### 1 jouju_main (서버 0)
      - 사용 모델  : NgRock, Flask 서버, GPT4(랭체인)
      - 서비스 기능 : 시크릿 주주와 음성 통화 및 영상 통화
  
### 2 gpt+bert (서버 1) : 텍스트를 인풋으로 받아 감정 분류 결과를 메인 서버에 전달한다.
      - 사용 모델  : koBERT ( GPT4 -> 메인 서버로 이동 )

### 3 tts_server (서버 2) : 텍스트를 인풋으로 받아 캐릭터의 음성을 메인 서버에 전달한다.
      - 사용 모델 : VITS (text -> Speech), RVC (데이터 가공 및 수집)
 
### 4 wj (서버 3) : 보이스(wav)와 감정(str)을 인풋으로 받아 캐릭터 영상을 메인 서버에 전달한다.  
      - 사용 모델  : Wav2Lip ( 보이스.wav + 캐릭터.mp4  => 입 합성 영상 ) 
      - 환경 : python3.7 CUDA 11.0
        환경 세팅 관련 노션 페이지
        https://brash-visitor-06b.notion.site/Wav2Lip-4dfa9b0d059144a789445dc0ceeac027?pvs=4
        Flask에 올리기 위한 세팅 관련 노션 페이지
        https://brash-visitor-06b.notion.site/Web-6a2df60d72bb499a9eead452fcc00472?pvs=4
      - 모델 : Wav2Lip + GAN,  s3fd-619a316812.pth(face_detection)
-->
