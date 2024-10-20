# 구현 기능 목록

## 사용자 입력

- [x]  “덧셈할 문자열을 입력해 주세요.”를 출력
- [x]  사용자가 문자열을 입력

## 문자열 검사

- [x]  문자열이 비었는지 검사
    - [x]  문자열이 비어있다면 0을 출력
- [x]  문자열에 숫자가 존재하는지 검사
    - [x]  숫자가 존재하지 않고 구분자만 있는지 검사
- [x]  커스텀 구분자를 사용하였는지 검사
    - [x]  문자열 앞부분의 "//"와 "\n”이 잘 입력되었는지 검사
    - [x]  커스텀 구분자를 사용하였다면 기본 구분자에 커스텀 구분자를 추가
- [x]  기본 구분자와 커스텀 구분자가 아닌 다른 문자가 있는지 검사
- [x]  숫자에 음수가 있는지 검사

## 계산기

- [x]  구분자를 문자열에서 제거하여 숫자를 추출하고 합을 구함
    
  
## 출력

- [x]  “결과 : 6”과 같이 숫자의 합을 출력

## 예외처리

- 사용자가 잘못된 값을 입력할 경우 `IllegalArgumentException`을 발생시킨 후 애플리케이션은 종료
