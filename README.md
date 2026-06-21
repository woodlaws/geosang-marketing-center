# 거상마케팅센터 AEO/GEO 무료 진단 랜딩페이지

별도 설치 없이 바로 실행하고 배포할 수 있는 정적 웹사이트입니다.

## 폴더 구성

```text
geosang-aeo-geo-vercel/
├─ index.html                  # 메인 페이지
├─ style.css                   # 디자인과 모바일 반응형 스타일
├─ script.js                   # FAQ, 상담 폼 안내 동작
└─ assets/
   └─ geosang-marketing.png    # 로고 이미지
```

## 내 컴퓨터에서 보기

1. `index.html` 파일을 더블 클릭합니다.
2. 브라우저에서 랜딩페이지가 열립니다.

## GitHub에 올리기

1. GitHub에서 새 저장소(Repository)를 만듭니다.
2. 이 폴더 안의 파일 전체를 업로드합니다.
3. `index.html` 파일이 최상위에 있는지 확인합니다.

## Vercel 배포 방법

1. Vercel에 로그인한 뒤 **Add New → Project**를 누릅니다.
2. GitHub에 올린 저장소를 선택합니다.
3. Framework Preset은 **Other**를 선택하거나 자동 감지를 그대로 둡니다.
4. Build Command와 Output Directory는 **비워 둡니다**.
5. **Deploy**를 누릅니다.

이 프로젝트는 순수 HTML/CSS/JavaScript 정적 사이트이므로 `vercel.json`, Node.js 설치, 빌드 명령이 필요하지 않습니다.

## 참고

- 상담 폼은 현재 데모입니다. 제출 시 화면에 완료 안내만 표시됩니다.
- 실제 상담 접수를 받으려면 Google Forms, Formspree, Tally 같은 폼 서비스 또는 별도 서버 연동을 추가하세요.
