# Baek Minwoo — Portfolio

> AI Engineer · Manufacturing AI Specialist · PhD @ Kyunghee University

## 🚀 배포 주소
GitHub Pages 활성화 후: `https://whitekun91.github.io/portfolio`

## 📁 구조
```
portfolio/
├── index.html   # 단일 파일 포트폴리오 (모든 CSS/JS 포함)
└── README.md
```

## 🛠 로컬 실행
```bash
# 브라우저에서 바로 열기
open index.html

# 또는 로컬 서버 실행
python3 -m http.server 8080
# → http://localhost:8080
```

## 📦 GitHub Pages 배포 방법
1. GitHub에서 `portfolio` 레포지토리 생성
2. 아래 명령어 실행:

```bash
git init
git add .
git commit -m "init: portfolio"
git branch -M main
git remote add origin https://github.com/whitekun91/portfolio.git
git push -u origin main
```

3. GitHub 레포지토리 → **Settings** → **Pages**
4. Source: `Deploy from a branch` → Branch: `main` / `/ (root)` → **Save**
5. 약 1~2분 후 `https://whitekun91.github.io/portfolio` 접속 확인

## ✏️ 수정 후 업데이트
```bash
git add index.html
git commit -m "update: portfolio content"
git push
```
