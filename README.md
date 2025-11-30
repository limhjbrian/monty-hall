# 몬티홀 문제 시뮬레이터

몬티홀 문제를 직접 체험해볼 수 있는 웹 애플리케이션입니다.

## 배포 방법 (Render)

1. GitHub에 코드 업로드
2. https://render.com 에서 계정 생성
3. "New +" → "Web Service" 선택
4. GitHub 저장소 연결
5. 설정:
   - **Name**: monty-hall (원하는 이름)
   - **Environment**: Python 3
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `python pybo.py`
6. "Create Web Service" 클릭

## 로컬 실행

```bash
pip install -r requirements.txt
python pybo.py
```

