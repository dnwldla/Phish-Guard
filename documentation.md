프로젝트 개요 및 주요 기능 설명. 기본 구조:

# PhishGuard

PhishGuard는 보이스피싱 탐지를 위한 AI 기반 웹 애플리케이션입니다.

## 주요 기능
- 텍스트 및 음성 입력을 통한 보이스피싱 탐지
- AI 분석 결과 제공
- 음성 응답 생성

## 기술 스택
- Flask
- OpenAI API
- Google Cloud Speech-to-Text & Text-to-Speech

설치 지침:

# 설치 지침

1. Python 3.8 이상 설치
2. 프로젝트 복제:
   ```bash
   git clone https://github.com/yourusername/PhishGuard.git
   cd PhishGuard

3. 로컬 환경 생성 및 활성화:
python -m flask run

4. 의존성 설치
pip install -r src/requirements.txt

5. .env 파일 구성
OPENAI_API_KEY, GOOGLE_APPLICATION_CREDENTIALS_PATH 추가
