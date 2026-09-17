# **🎓 VocaTutor \- 중·고등 영단어 예문 튜터**

**Google Gemini AI** 기반의 중·고등학생 맞춤형 영단어 예문 학습 및 문법 해설 모바일 웹 애플리케이션입니다.

## **📌 주요 특징 (Key Features)**

* **🎯 3단계 난이도별 맞춤 예문**:  
  * 중학교 필수 수준 (중2\~3)  
  * 고등학교 기본 수준 (고1\~2)  
  * 수능 및 심화 수준 (고3/수능)  
* **🔍 상세한 문법 및 구문 구조 해설**: 예문마다 핵심 문법 포인트, 끊어 읽기 팁, 문장 속 중요 어휘를 분해하여 해설 제공.  
* **💡 수능 & 내신 핵심 포인트**: 전치사 결합, 혼동 어휘, 수능 빈출 파악용 팁 정리.  
* **🔊 원어민 음성 듣기 (TTS)**: Web Speech API를 활용해 단어 및 예문 전체를 정교한 원어민 발음으로 재생.  
* **🧩 실전 복습 퀴즈**: 방금 학습한 단어를 바로 검증할 수 있는 빈칸 채우기 다지기 퀴즈 제공.  
* **🔑 사용자 Gemini API 키 설정**: 앱 상단 열쇠 메뉴를 통해 본인의 Google Gemini API 키를 저장(localStorage)하고 자유롭게 활용 가능.  
* **🔖 개인 단어장 (북마크)**: 복습하고 싶은 단어를 내 단어장에 저장하고 관리.  
* **📱 완벽한 모바일 최적화**: 스마트폰 화면 크기에 최적화된 앱 스타일 모바일 UX UI.

## **🛠 기술 스택 (Tech Stack)**

* **Frontend**: Vanilla HTML5, JavaScript (ES6+), Tailwind CSS (CDN)  
* **Icons & Fonts**: FontAwesome 6, Google Fonts (Noto Sans KR, Inter)  
* **AI Model**: Google Gemini API (gemini-2.5-flash)  
* **Audio**: Browser Native Web Speech API (SpeechSynthesis)

## **🚀 시작하기 (Getting Started)**

별도의 Node.js 설치나 빌드 과정 없이, 단일 HTML 파일로 즉시 실행할 수 있습니다.

### **1\. Repository 클론**

git clone https://github.com/your-username/voca-tutor.git  
cd voca-tutor

### **2\. 브라우저에서 실행**

* index.html 파일을 브라우저(Chrome, Edge, Safari 등)에서 직접 열어 실행합니다.

### **3\. Gemini API 키 설정 (선택 사항)**

1. [Google AI Studio](https://aistudio.google.com/)에서 발급받은 API 키를 준비합니다.  
2. 웹사이트 상단의 **🔑 열쇠 아이콘**을 클릭합니다.  
3. API 키를 입력하고 **저장하기**를 클릭합니다. (API 키는 브라우저의 localStorage에만 안전하게 저장됩니다.)

## **📸 주요 화면 구성 (Screenshots)**

| 메인 화면 및 검색 | 예문 3선 및 상세해설 | API 키 설정 및 단어장 |
| :---- | :---- | :---- |
| 단어 검색 및 추천 키워드 제공 | 중/고/수능 예문 및 퀴즈 제공 | 개인 API 키 저장 및 북마크 |

## **💡 사용 방법 (How to Use)**

1. **단어 검색**: 상단 검색창에 학습하고자 하는 영어 단어(예: consider, emphasize)를 입력합니다.  
2. **예문 분석 확인**:  
   * 3단계 난이도별 예문을 읽고 스피커 아이콘을 눌러 발음을 확인합니다.  
   * 예문 하단의 구문 분석 및 어휘 팁을 함께 학습합니다.  
3. **퀴즈 풀기**: 하단의 Instant Practice Quiz에서 올바른 단어를 선택하여 정답을 확인합니다.  
4. **단어장 저장**: 우측 상단의 북마크 버튼을 눌러 단어를 보관하고 필요할 때 단어장 메뉴에서 다시 복습합니다.

