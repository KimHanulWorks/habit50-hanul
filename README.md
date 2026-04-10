# 50일 습관 트래커

50일간의 습관을 관리하는 PWA 앱입니다. 건강 · 공부 · 시스템 카테고리별 미션 관리, 캘린더 체크, 슬로건 설정 기능을 제공합니다.

## 📱 핸드폰 앱으로 설치하기

### 1단계 — GitHub에 올리기

```bash
# 이 폴더에서 실행
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/50day-habit-tracker.git
git push -u origin main
```

### 2단계 — GitHub Pages 활성화

1. GitHub 저장소 → **Settings** 탭
2. 왼쪽 사이드바 → **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main** / **/ (root)** 선택 후 **Save**
5. 잠시 후 `https://YOUR_USERNAME.github.io/50day-habit-tracker/` 에서 접속 가능

### 3단계 — 홈 화면에 추가

**iPhone (Safari)**
> Safari로 접속 → 하단 공유 버튼(□↑) → **홈 화면에 추가** → 추가

**Android (Chrome)**
> Chrome으로 접속 → 우측 상단 메뉴(⋮) → **홈 화면에 추가** → 설치

---

## 기능

- ✦ **미션 관리** — 건강/공부/시스템 카테고리별 미션 추가·수정·삭제
- ◫ **캘린더** — 날짜별 미션 체크, 완료일 시각화
- ◎ **설정** — 시작일 설정, 진행 통계, 슬로건 입력
- 오프라인 작동 (Service Worker)
- 데이터 자동 저장 (localStorage)

## 파일 구조

```
50day-habit-tracker/
├── index.html      # 메인 앱
├── manifest.json   # PWA 설정
├── sw.js           # Service Worker (오프라인 지원)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```
