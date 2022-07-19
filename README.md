# 🫧 스스로 꾸준히 해 보는 REACT STUDY! 🫧

## `더북_리액트를 다루는 기술`과 함께합니다 ✨

### WHAT I LEARNED SO FAR 👩🏻‍💻

#### 📌 FIRST DAY

- [Chapter 1]

  - REACT에 대한 개념 잡기 ✔️
  - 작업 환경 공부 및 설정 완료 ✔️

- [Chapter 2]
  - JSX 문법, ESLint & Prettier 적용 공부 완료 ✔️

#### 📌 SECOND DAY

- [Chapter 3]

  - 클래스형 컴포넌트 ✔️
  - 컴포넌트 생성 ✔️
  - props ✔️

    - 함수형 컴포넌트에서의 props ✔️
    - 클래스형 컴포넌트에서의 props ✔️

  - state ✔️
    - 클래스형 컴포넌트의 state : **_`this.setState`_** 사용 ✔️
    - 함수형 컴포넌트의 state : **_`useState`에서 선언한 `세터 함수(Setter function)`_** 사용 ✔️

#### 📌 THIRD DAY

- [Chapter 4]

  - 리액트의 이벤트 시스템 ✔️
  - 이벤트 핸들링 : **_`함수형 컴포넌트 & 클래스형 컴포넌트 구현`_** 모두! ✔️

    - 컴포넌트 생성 및 불러오기 ✔️
    - onChange 이벤트 핸들링하기 ✔️
      - 렌더링을 하는 동시에 함수를 만들어서 전달하는 방법 ✔️
      - 함수(메서드)를 미리 준비하여 전달하는 방법 ✔️
    - input 여러개 다루기 : `e.target.name` 이용 ✔️

      - 함수형 컴포넌트 : `useState`를 쓸 때 인풋 값들이 들어있는 **_`form 객체`_** 를 사용하면 된다. ✔️

    - onKeyPress 이벤트 핸들링하기 ✔️

#### 📌 FOURTH DAY

- [Chapter 5]

  - ref 사용 상황 : 먼저 ref를 사용하지 않고도 원하는 기능을 구현할 수 있는지 반드시 고려한 후에 활용해라! ✔️

    - 특정 input에 포커스 주기 ✔️
    - 스크롤 박스 조작하기 ✔️
    - Canvas 요소에 그림 그리기 등 ✔️

  - ref 사용 ✔️

    - 콜백 함수 사용 ✔️
    - CreateRef ✔️

    ☝🏻 **새롭게 알게 된 내용** : `input.focus()`

  - 컴포넌트에 ref 달기 ✔️

    ☝🏻 **새롭게 알게 된 내용** : react에서의 `style` 중 `overflow` & `position`

#### 📌 FIFTH DAY

- [Chapter 6]

  - 리액트에서 반복적인 내용을 효율적으로 보여주고 관리하는 방법 ✔️

    - 자바 스크립트의 map 함수 ✔️
    - 데이터 배열을 컴포넌트 배열로 변환하기 ✔️
    - KEY ✔️
    - 동적인 배열 렌더링하기 ✔️

      - 초기 상태 설정 ✔️
      - 데이터 추가 기능 구현하기 : 불변성 유지를 위해 concat 함수 사용 ✔️
      - 데이터 삭제 기능 구현하기 : 불변성 유지를 위해 filter 함수 사용 ✔️

      ☝🏻 **새롭게 알게 된 내용** : `ul & li 태그`, `conct` 함수, `filter` 함수

      🍧 **중요 포인트** : 상태 안에서 배열을 변형할 때는 배열에 직접 접근하여 수정하는 것이 아니라, **`concat`, `filter` 등의 배열 내장 함수를 이용하여 새로운 배열을 만든 후 이를 새로운 상태로 설정**해 주어야 한다! 즉, **기존 상태를 그대로 두면서 새로운 값을 상태로 설정**해야 한다.

- [Chapter 7]

  - 라이프 사이클 메서드의 이해 ✔️

    - 마운트 ✔️
    - 업데이트 ✔️
    - 언마운트 ✔️

  - 라이프 사이클 메서드 구체적으로 살펴보기 ✔️

    ![image](https://user-images.githubusercontent.com/63195670/179726496-0ea069bb-7b68-4713-9c1f-4921fe2d1986.png)

    - 마운트 ✔️

      - constructor ✔️
      - getDerivedStateFromProps ✔️
      - render ✔️
      - componentDidMount ✔️

    - 업데이트 ✔️

      - getDerivedStateFromProps ✔️
      - shouldComponentUpdate ✔️
      - render ✔️
      - getSnapshotBeforeUpdate ✔️
      - componentDidUpdate ✔️

    - 언마운트 ✔️

      - componentWillUnmount ✔️

    - 에러 잡아내기 ✔️
      - componentDidCatch ✔️

  ☝🏻 **새롭게 알게 된 내용** : 랜덤 색상 생성하기
