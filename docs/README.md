## 🍚 메뉴 추천

- [ ] 코치 이름 입력 받기
- [ ] 각 코치가 먹지 못하는 메뉴 입력 받기
- [ ] 메뉴 추천
    - 카테고리는 2번 중복 가능
    - 메뉴는 중복 불가능 (코치끼리 중복은 가능)

## 🖥️ 입/출력 기능

- [ ] 시작 메세지 출력

#### 입력

- [ ] 코치 이름 입력 받기
- [ ] 코치가 먹지 못하는 메뉴 입력 받기

#### 출력

- [ ] 메뉴 추천 결과 메세지 출력
- [ ] 구분 메세지 출력
- [ ] 추천 메뉴 출력

## 👾 예외 상황

### [코치]

`[ERROR] 유효하지 않은 이름입니다. 다시 입력해 주세요.`

#### view

- [x] 빈 값을 입력한 경우
- [x] 한글이 아닌 다른 타입으로 입력한 경우
- [x] `,` 로 구분하지 않고 입력한 경우

#### domain

- [ ] 코치 인원수 검증
    - 2 - 5명 까지 유효
- [ ] 이름 길이 검증
    - 2 - 4글자 까지 유효

### [먹지 못하는 메뉴]

`[ERROR] 유효하지 않은 메뉴입니다. 다시 입력해 주세요.`

#### input

- [ ] 한글이 아닌 다른 타입으로 입력한 경우

#### domain

- [ ] 메뉴에 존재하지 않는 것을 입력한 경우
- [ ] 빈 값 입력 가능