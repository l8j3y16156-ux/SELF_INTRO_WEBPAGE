# 만드는 사람, 나 — GitHub Pages 배포 파일

현재 완성된 미색 홈페이지의 정적 배포본입니다. 새 Hello 참고 디자인은 아직 구현하지 않았습니다.

## 포함 파일

- `index.html`: 소개 본문, 프로필 원본, 이미지, 폰트, CSS, JavaScript가 모두 포함된 단일 HTML.
- `.nojekyll`: Jekyll 처리 없이 정적 파일 제공.

## GitHub 배포

1. ZIP 압축을 풉니다. ZIP 자체를 올리는 방식은 배포되지 않습니다.
2. GitHub 저장소에서 Add file → Upload files를 선택합니다.
3. `index.html`, `.nojekyll`, 이 README를 저장소 최상위에 올립니다. `index.html`이 하위 폴더에 들어가지 않게 합니다.
4. Settings → Pages → Deploy from a branch → main → /(root) → Save를 선택합니다.
5. 배포가 완료되면 Pages 화면에 표시되는 주소로 접속합니다.

별도 빌드·패키지 설치·이미지 폴더는 필요 없습니다. `.nojekyll`이 숨김 파일이라 보이지 않아도 단순한 이 HTML 페이지는 배포할 수 있습니다.

## 내용 및 연락처

사용자가 제공한 프로필 사진과 소개 원문을 포함합니다. 이메일은 JELEE@gmail.com, SNS는 Instagram 공식 예시 계정입니다. 링크 사용에는 인터넷이나 메일 앱이 필요합니다.

## 폰트와 사진

Pretendard Variable의 SIL Open Font License는 HTML 안에 포함되어 있습니다. 프로필은 사용자 원본입니다. 나머지 사진은 Unsplash 예시 사진이며 개인 촬영·제작 이력을 의미하지 않습니다.

## 검증 범위

원문 전문·프로필 바이트·이미지·폰트·스타일·스크립트 포함 여부와 JavaScript 문법을 검사했습니다. 실제 브라우저와 GitHub Pages 배포 후의 작동은 별도로 확인해야 합니다.
