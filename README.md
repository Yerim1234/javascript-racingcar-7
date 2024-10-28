# 자동차 경주

## 1. 자동차 이름 입력 받기

- 사용자는 쉼표로 구분된 자동차 이름을 입력한다.
- 이름은 5자 이하만 가능하며, 이를 검증한다.
- 잘못된 입력 시 "[ERROR]" 메시지와 함께 종료한다.

## 2. 시도 횟수 입력 받기

- 사용자는 경주 시도 횟수를 입력한다.
- 시도 횟수가 양의 정수인지 검증한다.
- 잘못된 입력 시 "[ERROR]" 메시지와 함께 종료한다.

## 3. 자동차 객체 생성하기

- 입력받은 이름들을 기반으로 자동차 객체들을 생성한다.

## 4. 자동차 경주 진행하기

- 주어진 횟수 동안 자동차들을 전진 또는 멈추게 한다.
- 각 턴마다 각 자동차는 0에서 9 사이의 무작위 값을 통해 전진 여부를 결정한다.
- 무작위 값이 4 이상인 경우 전진한다.

## 5. 차수별 경주 결과 출력하기

- 각 턴마다 모든 자동차의 진행 상태를 출력한다.

## 6. 우승자 결정 및 출력하기

- 모든 턴이 종료된 후, 가장 멀리 간 자동차를 우승자로 결정한다.
- 공동 우승자가 있을 경우, 쉼표로 구분하여 출력한다.

## 7. 입력 및 출력 로직 구현하기

- 사용자로부터 입력을 받고, 결과를 출력하는 콘솔 인터페이스를 구현한다.
- @woowacourse/mission-utils의 Console API를 사용하여 입력과 출력을 처리한다
