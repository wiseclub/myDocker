1
# Python Application Docker Image

이 프로젝트는 Python 애플리케이션을 Docker 컨테이너에서 실행하기 위한 환경을 제공합니다.

## 📦 포함된 내용

- Ubuntu 20.04 기반 이미지
- Python 3 및 pip 설치
- Python 종속성 설치 (`requirements.txt`)
- `app.py`를 기본 실행 엔트리포인트로 지정

## 🛠️ 빌드 방법

```bash
docker build -t python-app .
