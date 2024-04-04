# 과제 2 - 로또


## 🚀 기능 목록

- [X] 로또 구입 금액 입력 구현
    - [X] 1000원 단위로 입력 받는다.
        - [X] 1,000원으로 나누어 떨어지지 않는 경우 예외 처리
            - [X] IllegalArgumentException를 발생시키고, [ERROR]로 시작하는 에러 메세지를 출력한다.
            - [X] 입력을 다시 받는다.

---

- [X] 로또 발행 기능 구현
    - [X] 입력한 금액 / 1000만큼의 로또를 발행한다.
    - [X] 하나의 로또 당 6개의 서로 다른 숫자를 랜덤으로 생성한다.
    - [X] 1~45 사이의 숫자이다(1, 45를 포함).

---

- [X] 당첨 번호 입력 구현
    - [X] 6개의 숫자를 입력으로 받는다.
        - [X] 입력 값이 1-45 사이 숫자가 아닐 경우 예외 처리
        - [X] 입력 값 숫자가 서로 중복될 시 예외 처리
    - [X] 숫자는 쉼표(,)를 기준으로 구분한다.
        - [X] 입력 값이 쉼표로 구분이 안될 시 예외 처리
            - [X] IllegalArgumentException를 발생시키고, [ERROR]로 시작하는 에러 메세지를 출력한다.
            - [X] 입력을 다시 받는다.  
---

- [X] 보너스 번호 입력 구현
    - [X] 1개의 숫자를 입력으로 받는다.
        - [X] 입력 값이 1-45 사이 숫자가 아닐 경우 예외 처리
        - [X] 입력 값이 당첨 번호와 중복될 시 예외 처리
            - [X] IllegalArgumentException를 발생시키고, [ERROR]로 시작하는 에러 메세지를 출력한다.
            - [X] 입력을 다시 받는다.
---

- [X] 발행한 로또 수량 및 번호 출력 구현
    - [X] 발행한 로또 수량을 출력한다.
    - [X] 로또 번호를 오름차순으로 정렬해 출력한다.

---

- [X] 당첨 통계 출력 기능 구현
    - [X] 발행된 로또와 당첨 번호 간 번호가 일치한 개수를 확인한다.
    - [X] 3, 4, 5, 6개가 일치한 발행된 로또의 수를 출력한다.
    - [X] 수익률(당첨 금액 / 구입 금액)을 출력한다.
    - [X] 게임을 종료시킨다.

