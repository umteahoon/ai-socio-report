# -AI Socio Report-  
🤖 **AI 기반 사회 이슈·경제·전쟁 예측 웹서비스**

OpenAI GPT API를 활용하여  
사회·경제·전쟁 등 다양한 사회 문제를 AI가 예측·분석하는  
**웹 기반 리포트 플랫폼**을 개발하였습니다.

---

## 📌 프로젝트 개요

- **목표:** 사회적 이슈를 AI를 통해 자동으로 분석·예측하고, 보고서 형태로 공유하는 웹서비스 제작
- **기술 스택:** Next.js, React, Tailwind CSS, OpenAI API, Git
- **주요 기능:**
  - OpenAI GPT API를 활용한 AI 분석 리포트 자동 생성
  - 사용자 입력 기반 이슈 분석 요청 및 AI 결과 리포트 출력
  - AI 예측 리포트 공유 기능
  - 다크모드, 반응형 UI

---

## 🚀 실행 방법

### 1. 환경 준비

- **Node.js**
- **Git**
- (선택) **VS Code**

### 2. 프로젝트 실행

```bash
git clone https://github.com/your-username/ai-socio-report.git
cd ai-socio-report
npm install
```

> ⚠️ `.env.local` 파일을 프로젝트 루트에 생성하고, 아래처럼 **OpenAI API 키**를 설정하세요:

```
OPENAI_API_KEY=sk-xxxxx
```

---

### 3. 개발 서버 실행

```bash
npm run dev
```

- [http://localhost:3000](http://localhost:3000) 으로 접속

---

## 📁 프로젝트 구조

```
ai-socio-report/
│
├── app/                      
│   ├── api/                  
│   │   └── generate/         # AI 리포트 생성용 API 엔드포인트
│   │       └── route.js      
│   └── page.jsx              # 메인 페이지 (AI 리포트 생성 UI)
│
├── public/                   # 이미지, 파비콘 등 정적 파일
├── styles/                   # Tailwind CSS 설정
├── .env.local                # OpenAI API 키
├── package.json              
├── tailwind.config.js        
├── postcss.config.js         
└── README.md                 
```

---

## ✅ 주요 기능

1. ✅ AI 기반 사회 이슈 분석 리포트 생성
   - OpenAI GPT API를 활용하여 AI가 사용자의 입력에 맞춰 사회 이슈를 분석
   - GPT-3.5 또는 GPT-4 모델을 이용해 리포트를 작성

2. 🖱️ 사용자 입력 + 버튼 클릭
   - 사용자로부터 이슈나 상황을 입력받아 GPT API로 요청 전송
   - AI가 생성한 리포트를 실시간으로 받아와 화면에 출력

3. 📄 리포트 스타일 출력
   - 생성된 리포트를 뉴스 또는 보고서 스타일로 디자인
   - Tailwind CSS 기반으로 깔끔한 카드 형태로 리포트 제공

4. 🌙 다크모드 지원 + 반응형
   - 모바일, 데스크탑 모두 대응
   - 다크모드 버튼으로 색상 테마 전환 가능

5. 📤 향후 공유 기능 확장 예정
   - 생성된 리포트를 복사, 공유할 수 있는 기능 적용 예정
   - AI가 작성한 리포트를 SNS 등으로 쉽게 공유

---

## 🔧 향후 기능 개선 방안

- 🔍 이슈 카테고리 (경제, 전쟁, 사회 등) 선택 기능
- 📊 AI 리포트 자동 요약 / 하이라이트 표시
- 📁 리포트 자동 저장 (Firebase 또는 DB)
- 📈 트렌드 대시보드
- 🔥 인기 리포트 자동 추천

---

## 📚 사용한 API

- **OpenAI API (chat/completions)**
  - https://platform.openai.com/api-keys

---

## 🙋‍♂️ 개발자 정보

- **이름:** 엄태훈  
- **이메일:** am2869@naver.com  
- **GitHub:** [https://github.com/umteahoon](https://github.com/umteahoon)

---

## ✨ 한 줄 요약

> "AI가 사회 이슈를 읽고, 우리 대신 미래를 분석합니다."
