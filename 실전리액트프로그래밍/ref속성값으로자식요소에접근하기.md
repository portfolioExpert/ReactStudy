## ref 속성값으로 자식 요소에 접근하기

### ref 훅

<img width="290" alt="스크린샷 2022-03-22 오후 11 07 00" src="https://user-images.githubusercontent.com/52316270/159507716-1f41886e-7ccb-4081-97ab-8425988fe782.png">

- ref훅을 이용해 돔 요소에 focus를 주도록했다.

- current함수는 돔요소를 가리킨다.

- useEffect에 있는 ref가 있는 것은 실제 돔 요소는 렌더링 결과가 실제 돔에 반영된 후에 접근할 수 있기 때문에 부수효과 안에서 접근이 가능하다.

- useCallback을 이용해 함수를 고정시켜 이전에 생성된 값을 쓸 수 있도록 재사용시킨 것 이다.

  

### ref를 사용할 때 주의할 점

- 조건부 렌더링에서 ref의 current가 없을 수 있다. -> ref객체는 current 속성을 검사하는 코드가 필요하다.
