# 대구우리교회 성경찬송가

## 배포 방법

1. 이 폴더 전체를 GitHub 저장소에 올립니다
2. Netlify에서 해당 GitHub 저장소 연결
3. 빌드 설정 없이 자동 배포됩니다

## 암호 변경
`index.html` 파일 안에서 이 줄을 찾아 변경:
```
const PASSWORD = 'woori2024';
```

## 파일 구조
```
bible-site/
├── index.html          ← 메인 앱 (암호 변경은 여기서)
├── netlify.toml        ← Netlify 설정
└── data/
    ├── bible_nkrv.json ← 개역개정
    ├── bible_hrv.json  ← 개역한글
    ├── bible_niv.json  ← NIV
    └── hymns.js        ← 찬송가 625장 제목
```
