# 기능 명세서

## ⚡ 구현할 기능 목록
- [x]  게임 시작 문구를 출력한다.
  ```
  숫자 야구 게임을 시작합니다.
  ```
- [x]  컴퓨터(상대방)가 1에서 9까지 서로 다른 임의의 수 3개를 선택한다.
- [x]  플레이어로부터 서로다른 `3개의 숫자를 입력`받는다.
- [x]  잘못된 값을 입력한 경우 throw문을 사용해 예외를 발생시킨후 종료한다.
  - 3개의 숫자가 아닌 경우
- [x]  컴퓨터가 입력한 숫자에 대한 `결과를 출력`한다.
- [x]  컴퓨터가 선택한 3개의 숫자를 모두 맞히면 게임이 종료된다.
  ```
  3스트라이크
  3개의 숫자를 모두 맞히셨습니다! 게임 종료
  ```
- [x]  게임을 종료한 후 `다시 시작 여부를 입력 (1 or 2)`받는다.