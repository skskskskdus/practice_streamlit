# 📘 Streamlit 포켓몬 도감

<img width="1280" alt="image" src="https://github.com/user-attachments/assets/d1a3ff96-42d2-4142-a894-8919a526aa63" />

## Streamlit을 사용하여 만든 포켓몬 도감 웹 애플리케이션을 만들어봤습니다
## Streamlit을 활용하여 직관적인 UI와 간편한 데이터 입력을 구현했습니다.

### 📌 프로젝트 개요

#### 이 프로젝트는 streamlit을 사용하여 포켓몬 도감을 만드는 간단한 웹 애플리케이션입니다.
#### 사용자가 직접 포켓몬을 추가하고, 속성 선택 및 이미지 URL을 넣어서 추가할 수 있으며, 필요에 따라 삭제할 수도 있습니다.
#### Streamlit을 활용한 웹 개발을 연습해보고자 진행하였으며, UI 스타일링, sesstion_state활용법, 폼 입력 처리 등 개념을 적용해봤습니다!

## ✏️주요 기능
#### ✔️ 포켓몬 추가 기능(이름,속성,이미지 URL 입력)
#### ✔️ 포켓몬 속성 선택(최대 2개 선택 가능)
#### ✔️ 포켓몬 삭제 기능
#### ✔️ 예시 데이터 자동 완성 기능
#### ✔️ 반응형 UI 적용

##  🗂️ 프로젝트 구조

#### 📦 practice_streamlit
#### ├── 📄 app.py            //Streamlit 메인 코드
#### ├── 📂 images            // 기본 이미지 (로컬 저장)
####  ├── 📄 requirements.txt   // 필요한 라이브러리 목록
#### └── 📄 README.md         // 프로젝트 설명서

# 🪛 사용한 기술

####   Python 3.10.0
####   Steamlit
####   HTML + CSS(마크다운 스타일링)

# ⭐ 실행방법

### 1. 가상 환경 생성 및 실행

#### 프로젝트 폴더에서 실행

#### python -m venv venv
#### source venv/bin/activate  # macOS/Linux
#### venv\Scripts\activate  # Windows

### 2. 필수 패키지 설치

#### pip install -r requirements.txt

### 3. Streamlit 앱 실행
#### streamlit run app.py

### 📔 개발하면서 배운 점

#### 1. 전체적인 Streamlit UI 이해
#### 2. Streamlit의 from 입력 관리 및 session_state 사용
#### 3. HTML과 CSS를 활용한 UI 커스터마이징
