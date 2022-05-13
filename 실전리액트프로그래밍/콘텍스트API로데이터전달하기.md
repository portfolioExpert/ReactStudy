## 콘텍스트API로 데이터 전달하기

## Context

- 자식 컴포넌트에게 props를 이용해 넘겨주지 않고도 데이터를 제공할 수 있는 것

ex)코드

<img width="239" alt="스크린샷 2022-03-21 오후 9 43 14" src="https://user-images.githubusercontent.com/52316270/159282474-bd2390b9-6dbe-43e1-92e4-83f3a3fa27dd.png">


- 그림처럼 선언해주고 Greeting 에서 consumer를 해주면 위로 올라가서 provider를 찾아 그 값을 참조 provider를 찾지 못하면 초깃값을 참조한다.

- Provider 값이 변경되면 하위 Consumer 컴포넌트는 다시 렌더링 된다.

  

<img width="222" alt="스크린샷 2022-03-21 오후 9 50 11" src="https://user-images.githubusercontent.com/52316270/159283910-a824ca9b-13d8-4a21-b0d3-ebd8f6f54da6.png">

- Consumer 없이도 useContext 훅을 사용해 더 간편하게 사용할 수 있다.



### Context 사용시 주의할 점

- Consumer를 사용하는 쪽은 항상 Provider에서 렌더링이 되도록 작성 해야 한다.
