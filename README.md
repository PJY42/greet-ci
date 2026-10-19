# greet-week07

인사말 프로그램

## 설치 및 실행

### 실행
```bash
uv run --locked python greet.py Hee
uv run --locked python greet.py
```

### 테스트
```bash
uv run --locked pytest -q greet.py
```

### 코드 품질 검사
```bash
uv run --locked black --check greet.py
uv run --locked flake8 greet.py
uv run --locked mypy greet.py
```

### 패키지 빌드
```bash
uv build
```