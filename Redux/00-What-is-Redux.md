# Redux

### Redux란?

애플리케이션의 복잡성을 획기적으로 낮춰 우리의 코드가 어떤 결과를 보여줄지 예측가능하게 만들어주는 도구

### 왜 Redux를 사용할까?

한곳에 데이터를 집중해 관리해 다음과 같은 효과를 얻는다

1. 단 하나의 스테이트를 이용해 애플리케이션의 복잡성을 낮춘다.
2. 외부로부터 정보를 보안한다.(dispather, reducer로 정보수정 / getState로 정보 가져오기 때문에 각 부품(?)들은 독립성을 유지한다.)

# Redux를 효과적으로 사용하게 하는 도구

### Redux DevTools

- 버전관리(시간여행)을 가능하게 한다.
- 댜운로드, 업로드 과정을 통해 이전상태를 그대로 복원할 수 있다.

### Reducer

- console.log(action.type, action, state, newState);
- 다음과 같이 원하는 정보를 reducer안에서 한번에 호출 할 수 있다.


<img src="https://user-images.githubusercontent.com/60416187/125717829-9866efd4-203b-412a-b3ef-ec3e4431d011.png" width="600">
