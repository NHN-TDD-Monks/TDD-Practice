# TDD-Practice
TDD 수련을 위한 NHN Academy 학생들의 저장소

## TDD 프로젝트 진행 방향성
1. 켄트 백의 TDD 책을 참조하여 해당 프로젝트를 진행한다.
2. 프로젝트가 완료되면 각자의 브랜치에 머지한다.
3. 프로젝트가 끝나고 난 뒤에는 회고록을 짧게 한줄이라도 남기는 습관을 기르자. 3번 항목은 선택이다.

### 해당 프로젝트는 TDD 책의 xUnit이전까지만 다루는 프로젝트이다.

### TODO-LIST
* [ ] $5 + 10 CHF = $10 (환율이 2:1인 경우)
* [X] $5 * 2 = $10
* [ ] amount를 private으로 만들기
* [X] Dollar 부작용?
* [ ] Money 반올림?

## REVIEW
* chapter1. 다중통화를 지원하는 Money 객체
  * 진짜 작은 부분부터 테스트를 한다는 점이 신기하고 적응이 안됐다.
* chapter2. 타락한 객체
  * 컴파일 에러를 해결하기 위해 `return null;` 을 한다던지, 빠른 성공을 위해 바로 성공하는 값을 `return` 한다는 점이 아직은 크게 와닿지 않지만 빠르게 적응해야겠다.