# Eternity GitHub Pages 배포 안내

`eternity-github-pages-static.zip`의 압축을 해제한 뒤, 안에 들어 있는 모든 파일을 GitHub 저장소의 기본 브랜치 최상위에 올리세요. 저장소의 **Settings → Pages**에서 배포할 브랜치와 `/ (root)` 폴더를 선택하면 됩니다.

원본을 수정하려면 `eternity-project-source.zip`을 사용하세요. 프로젝트 폴더에서 `pnpm install`과 `pnpm build`를 실행하면 `dist/public` 폴더에 새 배포 파일이 만들어집니다. 이 폴더의 파일을 다시 GitHub Pages에 업로드하면 변경 사항이 반영됩니다.

> 팀원 편집 데이터와 프로필 이미지는 정적 웹사이트 특성상 각 방문자의 브라우저에만 저장됩니다. 전체 방문자에게 공통으로 보이게 하려면 별도 저장소 또는 서버 기능이 필요합니다.
