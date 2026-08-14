# Context Badge

Xcode 프로젝트 `Playground`(로컬: `~/Developer/Playground`)의 Context Badge 시나리오를 웹으로 옮긴 클릭 가능한 프로토타입입니다.

**Context Badge** — 홈 그리드 카드에 붙는 맥락 뱃지(Like 'OO', Trending in OO 등) 실험

- One Pager: https://app.notion.com/p/ridi/One-pager-3a52d79d77078063a164d6bd1179c950
- Figma: https://www.figma.com/design/RGRDcAJgYscJRhIxKIqni6/1.-2026-2Q?node-id=14682-55473

## 구조

`index.html` 하나로 완결된 정적 페이지입니다 (별도 빌드 스텝 없음). Manta 다크 토큰 색상, Poppins 폰트, 실제 표지 이미지를 전부 인라인(base64)으로 내장하고 있어 외부 리소스 없이 그대로 열립니다.

## 배포

https://manta-prototypes.vercel.app/context-badge/
