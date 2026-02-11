<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=250&section=header&text=Jaehak%20Kim&fontSize=80&fontAlignY=38&desc=AI%20Developer&descAlignY=55&descAlign=50)

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=3776AB&center=true&vCenter=true&width=600&lines=Full-Stack+AI+Developer;LLM+%26+RAG+Specialist;Django+%2B+AI+Integration)](https://git.io/typing-svg)

</div>

## 👨‍💻 About Me

```python
class AIEngineer:
    def __init__(self):
        self.name = "김재학 (Jaehak Kim)"
        self.education = "부산대학교 컴퓨터공학과"
        self.role = "AI & Full-Stack Developer"
        self.focus = ["LLM", "RAG", "Full-Stack Development"]
        
    def get_expertise(self):
        return {
            "AI/ML": ["LLM", "RAG", "NLP", "Transformers"],
            "Backend": ["Django", "Flask"],
            "Frontend": ["React", "HTML/CSS/JS", "Figma"],
            "Design": ["Figma", "Illustrator", "Photoshop"],
            "Data": ["TensorFlow", "scikit-learn", "Pandas"],
            "Deployment": ["AWS EC2"]
        }
```

<div align="center">

### 🔥 Core Tech Stack

#### AI & Machine Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗_Hugging_Face-FFD21E?style=for-the-badge&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/🦜_LangChain-1C3C3C?style=for-the-badge)

#### Full-Stack Development
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

#### Design & Tools
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Illustrator](https://img.shields.io/badge/Adobe_Illustrator-FF9A00?style=for-the-badge&logo=adobe-illustrator&logoColor=white)
![Photoshop](https://img.shields.io/badge/Adobe_Photoshop-31A8FF?style=for-the-badge&logo=adobe-photoshop&logoColor=white)

#### Database & Cloud
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

</div>

---

## 🚀 Featured Projects

### 🏠 법률 RAG AI 챗봇 (Legal RAG Chatbot)
**하이브리드 RAG 기반 주택 임대차 법률 상담 서비스**

<div align="center">

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![LangChain](https://img.shields.io/badge/🦜_LangChain-1C3C3C?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4o--mini-412991?style=for-the-badge&logo=openai&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone_Vector_DB-000000?style=for-the-badge)

![Upstage](https://img.shields.io/badge/Upstage_SOLAR_Pro2-FF6B6B?style=for-the-badge)
![Cohere](https://img.shields.io/badge/Cohere_Reranker-39594D?style=for-the-badge)
![EasyOCR](https://img.shields.io/badge/EasyOCR-4285F4?style=for-the-badge)
![Kiwipiepy](https://img.shields.io/badge/Kiwi_형태소분석-00D09C?style=for-the-badge)

![AWS](https://img.shields.io/badge/AWS_EC2-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

</div>

**핵심 기술**
- **Hybrid RAG**: Dense(Pinecone) + Sparse(BM25) 검색 결합
- **Query Normalization**: 일상어 → 법률 용어 자동 변환
- **Triple Retrieval**: 법령/규정/판례 멀티소스 검색
- **Cohere Reranking**: 검색 결과 정밀 재정렬
- **OCR Integration**: PDF/이미지 계약서 자동 분석

**성능 개선 (RAGAS 평가)**

| 지표 | 점수 | 의미 |
|------|------|------|
| **Context Recall** | **0.75** | 검색 재현율 |
| **Context Precision** | **1.00** | 검색 정밀도 |
| **Ri (Custom Score)** | **0.85** | 종합 검색 성능 지표 |
| Faithfulness | 0.34 | 답변 충실성 |
| Answer Relevancy | 0.41 | 답변 관련성 |

**주요 성과**
- ✅ **검색 정확도 최적화**: Dense + Sparse 통합 파이프라인으로 안정적 Recall 확보
- ✅ **Precision 100% 달성**: Cohere Reranker 적용으로 완벽한 정밀도 달성
- ✅ **LLM 모델 선정**: 6개 모델 비교 평가 → GPT-4o-mini 선정 (속도/비용/품질 최적)
- ✅ **Prompt 최적화**: 일반 상담 vs 계약서 분석 모드 분리로 실용성 향상

**팀 구성**: TEAM 안전한家 (4인)  
**개발 기간**: 2025.01.12 - 2025.02.10 (4주)  
**Status**: ✅ 완료

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/thre3o2wo/2ndTeamProject)
[![Live Demo](https://img.shields.io/badge/Live_Demo-FF6B6B?style=for-the-badge&logo=google-chrome&logoColor=white)](http://52.79.175.135)
[![YouTube](https://img.shields.io/badge/시연_영상-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=GFpilFkehSo)

</div>

---

### ⚡ 전력량 예측 AI (Power Consumption Prediction)
**날씨·시간 데이터 기반 전력 소비 예측**

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logoColor=black)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5424?style=for-the-badge&logoColor=white)

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

**성능 개선 과정**

| 모델 | 주요 변경사항 | RMSE | 개선율 |
|------|--------------|------|--------|
| **M1 (Baseline)** | SimpleDNN (날짜 미포함) | 162,100 | - |
| M2 | SimpleDNN (날짜 포함) | 164,830 | -1.7% ⬇️ |
| **M3** | **SimpleDNN (LAG 포함)** | **90,848** | **44% ⬆️** |
| M4 | SimpleDNN (LAG + 휴일) | 102,650 | 37% ⬆️ |
| M5-M7 | EmbeddingDNN 시도 | 93,998~161,411 | - |
| **M8 (최종)** | **LightGBM** | **89,264** | **45% ⬆️** |
| M9 | XGBoost | 132,887 | 18% ⬆️ |

**핵심 인사이트**
- ⚡ **Lag Feature가 핵심**: 과거 전력 사용량 데이터 추가로 44% 성능 향상
- 🌲 **LightGBM 최적**: Tree-based 모델이 시계열 패턴 학습에 더 효과적
- 📅 **단순 시간 정보는 오히려 독**: 날짜만 추가 시 오히려 성능 저하
- 🎯 **Feature Engineering > Model Architecture**: 모델보다 피처가 더 중요

**Features**
- LSTM, Ensemble 모델링
- 실시간 예측 웹 서비스
- 데이터 시각화 대시보드

**개발 기간**: 2024.12.22 - 2025.01.02 (2주)  
**Status**: ✅ 완료

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/seungdobaek/AIX_1stProject)

</div>

---

## 🎨 Frontend Portfolio

**웹 퍼블리싱 & 디자인 포트폴리오**

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Illustrator](https://img.shields.io/badge/Adobe_Illustrator-FF9A00?style=for-the-badge&logo=adobe-illustrator&logoColor=white)
![Photoshop](https://img.shields.io/badge/Adobe_Photoshop-31A8FF?style=for-the-badge&logo=adobe-photoshop&logoColor=white)

</div>

- **Skills**: PM, 기획, UI/UX 디자인
- **Certificate**: 일러스트 자격증

<div align="center">

[![Portfolio](https://img.shields.io/badge/View_Portfolio-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](http://taper44.dothome.co.kr/)

</div>

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jaynano44&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=70a5fd&icon_color=bf91f3&text_color=38bdae)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jaynano44&layout=compact&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=70a5fd&text_color=38bdae)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=jaynano44&theme=tokyonight&hide_border=true&background=1a1b27&ring=70a5fd&fire=bf91f3&currStreakLabel=70a5fd)

</div>

---

## 🎓 Education & Training

**KDT 기업맞춤형 AI-X 교육과정** (824시간)
- Python Full-Stack 개발
- AI/ML 모델링 및 LLM 활용
- 실전 프로젝트 기반 학습

[![학습일지](https://img.shields.io/badge/📚_Study_Log-0000FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jaynano44/ai)

---

<div align="center">

### 📫 Contact

[![Email](https://img.shields.io/badge/Email-taper44@hanmail.net-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:taper44@hanmail.net)
[![Phone](https://img.shields.io/badge/Phone-010--2570--1106-00C73C?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:010-2570-1106)
[![Portfolio](https://img.shields.io/badge/Portfolio-taper44.dothome.co.kr-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](http://taper44.dothome.co.kr/)

![footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=100&section=footer)

</div>
