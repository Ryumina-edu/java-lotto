# 로또

## 프로그래밍 요구사항
* [X] 규칙 3: 모든 원시값과 문자열을 포장한다
  * 로또 숫자 하나(int)를 추상화한 LottoNo 객체를 추가해 구현한다
  * 구입 금액(int)을 추상화한 Cash 객체 추가
* [X] 규칙 8: 일급 콜렉션을 쓴다
  * 추첨 결과 리스트(List<Rank>)를 Result 객체로 추가 
* [X] 규칙 9: 게터/세터/프로퍼티를 쓰지 않는다(최소화)

## 4단계 기능 요구사항
* [X] 수동으로 구매할 로또 수를 입력 받는다(InputView)
* [X] 해당 수만큼 수동으로 로또 번호를 입력 받는다(InputView)
* [X] 수동 입력을 제외하고 나머지 금액에 대한 자동 로또 번호를 생성한다
* [X] 잘못된 입력값에 대해 예외 처리한다