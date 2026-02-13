# SMC Consulting Report Web Form

점포 관리 컨설팅 리포트를 **단일 HTML 파일(`index.html`)**로 운영할 수 있도록 구성한 프로젝트입니다.

## 1) 로컬 실행

```bash
python -m http.server 4173
```

브라우저에서 아래 주소를 열면 됩니다.

- http://localhost:4173/index.html

---

## 2) GitHub에 연동(처음 1회)

아래에서 `YOUR_ACCOUNT`, `YOUR_REPO`를 실제 값으로 바꿔 실행하세요.

```bash
git init
git add .
git commit -m "init: consulting report web form"
git branch -M main
git remote add origin https://github.com/YOUR_ACCOUNT/YOUR_REPO.git
git push -u origin main
```

이미 Git 저장소라면 `remote`만 연결하면 됩니다.

```bash
git remote -v
git remote add origin https://github.com/YOUR_ACCOUNT/YOUR_REPO.git
# 또는 기존 origin 교체
# git remote set-url origin https://github.com/YOUR_ACCOUNT/YOUR_REPO.git
git push -u origin main
```

---

## 3) GitHub Pages로 배포(선택)

1. GitHub 저장소 → **Settings** → **Pages**
2. **Source**를 `Deploy from a branch`로 선택
3. Branch를 `main` / `/ (root)`로 선택 후 저장
4. 배포 URL 접속
   - 예: `https://YOUR_ACCOUNT.github.io/YOUR_REPO/`

---

## 4) 프로젝트 구성

- `index.html`: 컨설팅 리포트 폼의 전체 코드(스타일/스크립트 포함)
- `README.md`: 실행 및 GitHub 연동 가이드

