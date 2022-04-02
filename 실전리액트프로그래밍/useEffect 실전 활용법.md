## useEffect 실전 활용법

- useEffect는 컴포넌트가 렌더링 될때 호출된다. 따라서, 서버에서 데이터를 request하는 경우 값이 변하지 않는다면 재 렌더링을 피하기 위해 의존성 배열을 작성해주어야 한다.
- useEffect는 async await 함수로 만들면 문제가 되는데 항상 반환 값은 함수 타입이어야 하기 때문 -> async await의 반환값은 Promise객체이기 때문