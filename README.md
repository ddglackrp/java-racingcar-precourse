# java-racingcar-precourse

# 기능 요구 사항
- 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
- 각 자동차에 이름을 부여할 수 있다. 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.
- 자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능하다.
- 사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
- 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
- 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.
- 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.
- 사용자가 잘못된 값을 입력할 경우 를 발생시키고, "[ERROR]"로 시작하는 에러 메시지를 출력 후 그 부분부터 입력을 다시 받는다. 

# 구현 기능 목록
- Controller
  - ~~입력 컨트롤러~~
    - ~~자동차 이름 입력 처리~~
    - ~~시도 횟수 입력 처리~~
  - 레이싱 컨트롤러
    - 레이싱 전체 진행 (입력 처리, 레이싱 시작, 우승자 출력)
    - 레이싱 참여 자동차 레이싱 시작
- Model
  - ~~자동차~~
  - 레이싱 참여 자동차
    - ~~레이싱 참여 자동차 추가~~
    - ~~우승자 위치 정보~~
    - ~~우승자 이름 정보~~
  - ~~사용자 입력 유효성 검사~~
    - ~~자동차 이름 입력 유효성 검사~~
    - ~~시도 횟수 입력 유효성 검사~~
- view
  - ~~유저 입력~~
  - 유저 출력
    - ~~1회 실행 결과 출력~~
    - ~~우승자 출력~~
- utils
  - ~~난수 생성기~~
