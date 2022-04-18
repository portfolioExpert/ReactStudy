 ## React-Redux 사용하기

- 전체를 Provider로 감싸준다
- Provider는 리액트에서 액션이 처리 되었을 때 이벤트를 받아서 하위에 있는 컴포넌트가 다시 렌더링 될 수 있도록 도와줍니다.
- 리덕스에서 데이터를 가져올 때 useSelector를 이용한다. ->함수가 반환하는 값이 그대로 훅의 반환 값이 된다.
  - Ex) const friends = useSelector(state => state.friend.friends)
- useSelector는 액션 처리 후 이전값을 기억했다가 값이 변경 되었을 때 컴포넌트를 다시 렌더링 시켜준다.