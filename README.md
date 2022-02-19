# commit-message-style-guide

### Commit Message Format
```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

### Type
- **feat**: 새로운 기능 추가, 요구 사항 변경으로 인해 기존 기능 변경
- **fix**: 버그 수정
- **docs**: 문서 추가 및 수정 (주석 등)
- **style**: 코드 스타일 수정 (포매팅, 세미콜론 누락 등)
- **refactor**: 프로덕션 코드 리팩토링 (버그 수정이나 기능 추가를 제외한 코드 변경)
- **test**: 테스트 코드 추가 및 리팩토링 (기능을 구현할 때 테스트 코드를 함께 작성했다면 feat 사용)
- **chore**: 빌드, 배포 등 기타 작업들을 추가 및 수정
- **rename**: 파일명 변경
- **remove**: 파일 삭제
- **revert**: 작업 되돌리기

### References
- https://udacity.github.io/git-styleguide/
- https://pages.nist.gov/dioptra/dev-guide/contributing-commit-styleguide.html
- https://blog.munilive.com/posts/my-git-commit-guide.html
- https://nohack.tistory.com/17
