## create-react-app으로 시작하기

- 리액트 개발 환경을 직접 구축하려면..

- webpack, babel -> 빌드 시스템 환경 구축을 위해

- Jest -> 테스트 환경을 구축하기 위해

- eslint -> 코딩 컨벤션을 자동으로 체크하기 위해

- polyfill -> 오래된 브라우저를 지원하기 위해

- HMR(Hot Module Replacement) -> 코드를 수정하면 화면에 바로바로 적용되도록 하는 것

  -> create-react-app이 모두 담고있다.

### 특징

- 빌드 시스템, eslint 등의 설정을 거의 변경할 수 없다.
- SSR(Server Side Rendering)을 지원하지 않는다.
- 백 오피스에 적합

### CRA 명령어

- Start: 개발 도중 변경된 코드를 실험, 개발모드로 실행

  + https로 실행 : HTTPS=true npm start

- Build: 정적 파일이 생성되며, 배포할 때 실행 -> CloudFront S3에 업로드 할 때 적합

- Test: 배포 전 test에 통과하는지 알아보기 위해 실행하는 것

- Eject: 모든 설정 파일을 추출하는 명령어 -> CRA를 기반으로 직접 개발환경을 구축하고 싶을 때 적합

  

