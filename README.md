# 0.0 왜 Dart인가?
1. 다양한 Platform
  - DartNative / DartWeb
2. 두가지 Compile 방식
  - JIT(Just-in-time) / AOT(Ahead-of-time)
  - JIT: 개발용. 즉시 코드를 화면에 제시함. 모바일 개발에 적합함.
  - AOT: 코드를 먼저 작성하고 이후에 작동시킴
3. Null Safety
  - 모바일 개발 중 자주 발생하는 에러를 잡아줌.
4. Dart-Flutter의 긴밀한 협업 개발
  - 언어와 프레임워크의 적합성이 높음.

# 0.1 개발환경 설정하기
- [DartPad](https://dartpad.dev/)
- `main` 함수는 반드시 필요하다
- 코드가 끝나면 반드시 `;`를 넣어준다
- 변수 선언은 `var`로 시작한다
  ```dart
  void main() {
    var name = 'nico';
    String place = 'school';
  }
  ```
  - var는 변수형을 예측한다
  - var 대신 직접 자료형을 제시할 수도 있다
- 변수값을 수정할 때는 이전 값의 자료형을 유지해야 한다
  ```dart
  void main() {
    var name = 'nico';
    name = 'noru';
  }
  ```