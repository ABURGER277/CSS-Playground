# CSS-Playground

## 디자인 및 레이아웃
- **기본 디자인**:
  - 불필요한 화려한 디자인 요소를 최소화하고, 콘텐츠 전달에 집중한다.
- **반응형 레이아웃**:
  - 헤더(header) 아래에 콘텐츠 본문(contents body)을 배치하고,
  - $n \times m$ 형태로 카드(card) 컴포넌트를 반복 배치한다.
  - 카드 사이즈와 1열당 개수는 모바일, 태블릿, 데스크톱 환경 모두에서 반응형으로 동작하도록 CSS를 설계한다.
  - 카드 클릭시 보여질 `Article`은 굳이 반응형으로 제작하지 않는다.


## 네비게이션 및 라우팅
- **카드 클릭 시 이동**:
  - 각 카드 클릭 시 해당 카드의 도메인에 해당하는 URL로 이동한다.
  - 이동 페이지(Article Page)에서는 CSS Property를 테스트하거나, 특정 기능을 시연할 수 있는 페이지로 구성한다.

## 컨텐츠 관리
- **Article Page 관리 효율성**:
  - Article Page의 내용(html 파일, 스크립트 등)을 최소한의 관리 포인트에서 유지할 수 있는 방법을 모색한다.

## 배포 전략
- ~~현재는 `Netlify`(네틀리파이)로 배포를 예정중이다.~~
  - Vercel로 배포 완료
- `GitHub main branch`에 `push`하면 자동으로 배포될 `CI/CD`파이프라인을 구축하도록 한다.
  - develop branch 추가 생성 후 일괄 푸쉬
