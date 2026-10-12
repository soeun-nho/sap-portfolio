# 노소은 SAP ERP 포트폴리오

GitHub Pages 제출용 정적 웹페이지입니다. 별도의 설치나 빌드 과정이 필요하지 않습니다.

## GitHub Pages 게시 방법

1. GitHub에서 `portfolio`라는 Public 저장소를 만듭니다.
2. 이 폴더 안의 파일과 `assets` 폴더를 저장소 최상위에 모두 업로드합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Source**에서 `Deploy from a branch`를 선택합니다.
5. Branch는 `main`, 폴더는 `/(root)`를 선택하고 저장합니다.
6. 생성된 `https://아이디.github.io/portfolio/` 주소를 시크릿 창에서 확인합니다.

## 파일 구조

```text
portfolio/
├── index.html
├── styles.css
├── script.js
├── .nojekyll
└── assets/
    ├── portfolio-cover.jpg
    ├── soeun-noh-sap-portfolio.pdf
    └── pages/
        └── page-1.jpg ... page-9.jpg
```

PDF를 교체할 때는 새 파일명을 `soeun-noh-sap-portfolio.pdf`로 맞추면 웹페이지를 수정하지 않아도 됩니다.
