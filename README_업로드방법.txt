KDYON WEBSITE — GitHub Pages Upload Package

[가장 쉬운 업로드 방법]
1. 이 ZIP 파일을 PC에서 압축 해제합니다.
2. GitHub의 kdyon/kdyon.github.io 저장소로 이동합니다.
3. 화면의 'uploading an existing file / 기존 파일 업로드'를 클릭합니다.
4. 압축 해제한 KDYON_WEBSITE 폴더 안의 파일과 assets 폴더를 모두 업로드합니다.
   - ZIP 파일 자체를 올리는 것이 아닙니다.
   - index.html, styles.css, script.js 등이 저장소 최상위(root)에 보여야 합니다.
5. Commit changes를 누릅니다.
6. 저장소의 Settings > Pages로 이동합니다.
7. Source가 'Deploy from a branch'라면 Branch = main, Folder = /(root) 를 선택하고 Save합니다.
8. 1~5분 정도 기다린 뒤 https://kdyon.github.io 에 접속합니다.

[사이트가 정상적으로 보인 다음]
- kdyon.com 연결을 진행합니다.
- GitHub Settings > Pages > Custom domain에 kdyon.com 입력
- 그 다음 Gabia DNS 레코드를 설정
- DNS 확인 후 Enforce HTTPS 활성화

[현재 사이트에 들어간 정보]
- 회사/브랜드: KDYON
- Descriptor: GLOBAL COMMERCE & BRANDS
- 메인 메시지: Korea to Global.
- Commerce Brand: KOREA PICK by KDYON
- Contact: koreapick.jp@gmail.com
- 사업자번호, 주소, 법인명/Co., Ltd.는 아직 넣지 않았습니다.

[주요 파일]
- index.html : 홈페이지 본문
- styles.css : 전체 디자인/모바일 반응형
- script.js : 모바일 메뉴/스크롤 애니메이션
- assets/ : 로고, 파비콘, 앱 아이콘
- robots.txt / sitemap.xml : 검색엔진 기본 설정
- 404.html : 잘못된 주소 접근 시 홈으로 이동

[수정 시 주의]
- 로고 파일명은 바꾸지 않는 것이 가장 안전합니다.
- 향후 회사 이메일이 생기면 index.html의 koreapick.jp@gmail.com 부분만 교체하면 됩니다.
- 사업자등록 후 법인명/사업자정보/주소는 그때 Footer 또는 Contact 영역에 추가하면 됩니다.
