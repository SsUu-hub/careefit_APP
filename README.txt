CareeFit PWA 배포 안내

1. ZIP 압축을 풀고 안의 5개 파일을 GitHub의 ssuu-hub/careefit 저장소 최상위 폴더에 업로드하세요.
   index.html / manifest.webmanifest / service-worker.js / icon-192.png / icon-512.png
2. 기존 index.html이 있으면 새로운 index.html로 교체(덮어쓰기)하세요.
3. GitHub Pages 주소 https://ssuu-hub.github.io/careefit/ 가 새 버전으로 바뀌었는지 확인하세요.
4. 갤럭시 Chrome에서 주소를 직접 열고 메뉴(⋮) > 설치 또는 홈 화면에 추가를 확인하세요.
5. 여전히 설치 불가라면 기존에 설치한 CareeFit 웹앱/바로가기를 먼저 정리하고 Chrome을 완전히 닫았다가 다시 열어 보세요.

중요: 이 압축의 아이콘은 임시 C 로고입니다. 기존 피키 로고 이미지가 있다면 icon-192.png와 icon-512.png를 해당 이미지로 바꿔 넣을 수 있습니다.
기존 HTML 화면/앱 로직은 그대로 두고, head 메타정보 및 서비스 워커 등록만 추가했습니다.
사이트 배포 및 실제 휴대전화 크롬의 설치 성공 여부는 여기에서 실기기 검증하지 않았습니다.
