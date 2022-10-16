# 사다리 게임
## 기능 요구 사항
* 사다리 게임에 참여하는 사람에 이름을 최대5글자까지 부여할 수 있다. 사다리를 출력할 때 사람 이름도 같이 출력한다.
* 사람 이름은 쉼표(,)를 기준으로 구분한다.
* 사람 이름을 5자 기준으로 출력하기 때문에 사다리 폭도 넓어져야 한다.
* 사다리 타기가 정상적으로 동작하려면 라인이 겹치지 않도록 해야 한다.
* |-----|-----| 모양과 같이 가로 라인이 겹치는 경우 어느 방향으로 이동할지 결정할 수 없다.
* 사다리 실행 결과를 출력해야 한다. 
* 개인별 이름을 입력하면 개인별 결과를 출력하고, "all"을 입력하면 전체 참여자의 실행 결과를 출력한다.

## 기능목록
- [x] 이름 입력
  - [x] ,을 기준으로 입력
  - [x] 공백 or 5자 초과 시 예외
  - [x] all 이름은 예외 처리 할 것
  - [x] 일정한 간격으로 이름 출력
- [x] 사다리 높이 입력 받아, 길이 만큼의 사다리 생성
  - [x] 사다리 높이 입력 
  - [x] 사용자 수 만큼의 세로 줄, 사다리 높이 만큼의 가로 줄을 가지는 Ladder 생성
  - [x] 가로 라인이 겹치지 않는 Rule 적용 할 것
- [x] 생성한 사다리 출력
- [x] 사다리 게임에 대한 보상 입력
  - [x] 입력한 이름의 갯수와 맞는지 체크
- [x] 사다리 게임에 대한 보상 출력
