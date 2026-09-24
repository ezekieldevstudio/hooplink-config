# Hooplink Config

Hooplink용 공개 정적 설정 저장소입니다. 설치나 빌드 과정이 없습니다.

## 파일

- `config.json`: 앱 버전, 점검 여부, 공지사항·FAQ 파일 경로
- `faq.json`: FAQ
- `notices.json`: 공지사항

참조 프로젝트처럼 루트에 정적 파일을 배치하며, JSON은 how-much-config의 schemaVersion 및 version/items 형식을 따릅니다. 앱에 불필요한 광고·추천 설정은 추가하지 않았습니다.

## 사용

main 브랜치에 게시한 파일은 다음 주소로 읽을 수 있습니다.

- https://raw.githubusercontent.com/ezekieldevstudio/hooplink-config/main/config.json
- https://raw.githubusercontent.com/ezekieldevstudio/hooplink-config/main/faq.json
- https://raw.githubusercontent.com/ezekieldevstudio/hooplink-config/main/notices.json

내용 변경 시 해당 파일의 version과 config.json의 content 버전을 함께 올리고 updatedAt을 갱신합니다.

## 후속 작업

- Hooplink 앱에서 설정을 가져오는 코드는 별도로 연결해야 합니다. 이 저장소 생성만으로 앱 동작이 변경되지는 않습니다.
- 개인정보처리방침은 Hooplink의 실제 데이터 처리와 운영 정책을 확인한 후 작성하고 privacyPolicyUrl을 추가합니다.
- GitHub Pages가 필요하면 Settings → Pages에서 main / (root)를 게시 소스로 설정합니다. 현재 Pages 배포는 설정하지 않았습니다.

비밀키, 인증 토큰, JKS, signing.properties, keys 폴더 및 사용자 개인정보를 이 공개 저장소에 추가하지 않습니다.
