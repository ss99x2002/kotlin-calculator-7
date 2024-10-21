# kotlin-calculator-precourse

## 기능 구현 목록
### 입력
- 문자열을 입력 받는 메시지를 출력하고, 문자열을 입력 받는다.
- 입력이 비어있을 시 IllegalArgumentException 을 발생시키고 종료한다.
  
### 구분자 추출
- 커스텀 구분자가 있는지 확인하고, 구분자를 추출한다. 
- 만약 커스텀 구분자가 없다면 ':' , ','를 기본 구분자로 사용한다.
-  // \n 방식이 아닌 커스텀 구분자 지정 시 IllegalArgumentException 을 발생시키고 종료한다.

### 숫자 추출 
- 구분자를 기준으로 문자열 내에 숫자를 추출한다.
- 구분자 또는 숫자가 아닌 값이 있을 시 IllegalArgumentException 을 발생시키고 종료한다.
- 양수가 아닌 값이 있을 시 IllegalArgumentException 을 발생시키고 종료한다.

### 숫자 덧셈
- 추출된 숫자들을 합산하여 결과로 출력한다. 
