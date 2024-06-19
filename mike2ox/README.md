# Project Repo

- [my-tiny-grep-by-rust](https://github.com/mike2ox/my-tiny-grep-by-rust)

## Process

### 24.06.05

- 여행으로 인해 진행 X

### 24.06.12

- 12.1. 커맨드 라인 인수 받기 ✅
- 12.2. 파일 읽기 ✅
- 12.3. 모듈성과 에러 처리 향상을 위한 리팩터링 ✅

### 24.06.19

- 진행 X
- 휴일에 온라인 모각작을 진행할 예정

## Study

### 12.1

- (pending)

### 12.2

- (pending)

### 12.3

- 프로그램의 구조적, 잠재적 에러처리 방식과 유지보수를 위한 코드 구조화에 대한 고민
  - 역활에 따라 코드를 분리하는 것이 좋다.(1)
  - 의미있는 변수들끼리 구조체로 묶어서 관리하는 것이 좋다.(2)
  - 에러 케이스별로 에러 메세지를 출력하는 것이 좋다.(3)
  - 에러 처리의 유지보수를 위해 한 곳에서 관리하는 것이 좋다.(4)

## 궁금한 점

- main 함수의 입력부에는 별도의 변수가 없는건가? (ex. c 언어의 argc, argv)
  => [참고하자](https://www.reddit.com/r/rust/comments/7ud3mh/beginner_question_main_function_arguments)

- clone을 남발하면 결국 기존 C계열의 메모리 관리와 다를바 없지 않을까? 그러고도 Rust를 사용할 이유가 있을까?
  => 너무 빡빡하게 잡는 것도 잘못된 것 같다. 실제로 unsafe를 만들어 놓은 것도 그런 의도가 아닐까?
