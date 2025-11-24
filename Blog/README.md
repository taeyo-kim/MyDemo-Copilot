# Django 블로그 프로젝트

Django 기반의 블로그 웹 애플리케이션입니다.

## 주요 기능
- 사용자 로그인 및 회원가입
- 블로그 글 작성, 수정, 삭제
- 블로그 글 목록 조회

## 기술 스택
- **Backend**: Django Framework
- **Frontend**: Django Templates + TailwindCSS
- **Database**: SQLite (개발용)
- **Authentication**: Django 내장 인증 시스템

## 설치 및 실행

### 1. 가상환경 생성 및 활성화
```powershell
python -m venv venv
venv\Scripts\activate
```

### 2. 패키지 설치
```powershell
pip install -r requirements.txt
```

### 3. 환경 변수 설정
`.env` 파일에서 `SECRET_KEY`를 변경하세요.

### 4. 다음 단계
프로젝트 설정 및 앱 구현은 GitHub Issues를 참고하세요.

## 참고 문서
- [blog.instructions.md](.github/instructions/blog.instructions.md)
