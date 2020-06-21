# To-do 리스트 Redux를 사용하여 리팩터링 하기

지금은 모든 상태를 `App` 컴포넌트가 관리하고 있습니다. `Redux`가 관리하도록 리팩터링을 해주세요.

## 과제 목표

상태관리를 `Redux`로 변경해도 모든 컴포넌트 테스트가 통과해야합니다. 추가로 `reducer`들에 테스트를 추가해주세요.

## 제한 조건

* `if`는 사용할 수 있어도 `else` 사용하실 수 없습니다. `GuardClauses` 방법을 사용해주세요.
* `switch`는 사용하실 수 없습니다.
* `let`은 사용하실 수 없습니다. `const`만을 사용하여 문제를 해결해주세요.
* 함수 이름과 변수 이름에 줄임말은 사용하실 수 없습니다. 길더라도 명확하게 써주세요.
* indent(인덴트, 들여쓰기) depth를 1로 유지해주세요.
예를 들어, for문 안에 if문이 있으면 indent depth는 2입니다.
depth를 줄이는 좋은 방법은 함수(또는 메소드)를 분리하면 됩니다.

## 설치하기

```bash
npm install
```

## 실행하기

```bash
npm start
```

자동으로 브라우저가 켜지지는 않으니 브라우저에 `http://localhost:8080`을 입력하여 접속해 주세요.  

만약 현재 컴퓨터에서 이미 `8080`이라는 포트를 사용하고 있다면 `8081`으로 실행이 될 수도 있어요. 만약 `8081`도 사용하고 있으면 `8082`, `8083` ... 순서대로 찾아서 만들어집니다.

## 린트 실행하기

```bash
npm run lint
```

## 테스트 실행하기

### 전체 테스트 실행하기

```bash
npm test
```

### 유닛 테스트 실행하기

```bash
npm run test:unit

# 파일이 저장됐을 때 자동으로 테스트 실행하기
npm run test:unit -- --watch-all

# 커버리지 출력하기
npm run coverage
```

### e2e 테스트 실행하기

서버가 실행중인 상태에서 테스트를 실행해야 합니다.

```bash
npm run test:e2e
```
