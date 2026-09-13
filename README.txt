포트폴리오 페이지 사용법
=======================

[1] 사진 넣기 (선택)

images 폴더에 아래 이름 그대로 저장하면 해당 위치에 자동으로 들어갑니다.
파일이 없으면 그 사진 영역은 알아서 사라지므로, 있는 것만 넣어도 됩니다.

  images/fittrace-product.jpg   → 핏트레이스 완제품 사진
  images/fittrace-parts.jpg     → 부품 / 조립 과정 / 생산 현장 사진
  images/gitty-screen.jpg       → GITTY 서비스 화면 캡처
  images/capstone-kennel.jpg    → 캡스톤 안전 커넬 제작물 사진

- 확장자가 png라면 index.html에서 .jpg를 .png로 바꿔주세요.
- 가로 1200px 내외면 충분합니다. 파일당 500KB 이하 권장.
- 사진을 더 넣고 싶으면 index.html에서 <figure> 블록을 복사해 쓰면 됩니다.


[2] 인터넷에 올리기 (셋 중 하나)

A. Vercel  ← GITTY를 이미 Vercel로 운영 중이면 가장 빠름
   1. vercel.com/new 접속
   2. 이 portfolio 폴더를 통째로 드래그 앤 드롭
   3. Deploy → 몇 초 뒤 https://xxxx.vercel.app 주소 발급

B. Netlify
   1. app.netlify.com/drop 접속 (로그인)
   2. portfolio 폴더를 드래그 앤 드롭

C. GitHub Pages
   1. 새 저장소를 만들고 파일 업로드
   2. Settings → Pages → Branch: main / (root) → Save

발급된 주소를 LIG 지원서의
"본인의 경험 및 성과를 보여줄 수 있는 온라인 자료 링크" 칸에 붙여넣으면 됩니다.


[3] 경력기술서 PDF

career-yoo-byonghyeon.pdf 파일이 폴더에 함께 들어 있습니다.
페이지 상단과 하단의 '경력기술서 PDF' 링크가 이 파일을 엽니다.
폴더째로 올리면 자동으로 같이 배포되므로 따로 할 일은 없습니다.
PDF를 새로 고쳤을 때는 같은 이름으로 덮어쓰고 다시 배포하면 됩니다.


[4] 내용 수정

index.html을 메모장이나 VS Code로 열어 글자를 고치면 됩니다.
문장은 모두 <section> 태그 안에 순서대로 들어 있습니다.
