# [dart 기초]

# 기본 형태 - 줄을 세미콜론 단위로 구분한다.

```dart
void main() {
	
}
```

## 출력 함수 - 문자열을 출력

```dart
print("");
```

# 변수 선언 - var (변수명) = 값;

```dart
var a = 0;
```

Dart는 변수 선언에 자료형이 필요하지 않다 << 처음 할당된 자료형으로 자동 변환된다.

Dart에서 변수 재정의는 불가능하다.

- 재정의를 한다면
    
    ```dart
    var a = 0;
    var a = 1;
    ```
    
    오류
    

## 변수 선언 - C처럼 선언

```dart
int a = 1;
String b = "ABC";
```

char는 없고 C처럼 선언하면 된다.

## 대입 연산자의 사용 - C처럼 쓰자

```dart
var a = 1;
print(a);
a = 2;
print(a);
```

하나의 변수 a를 사용하여 두 값을 출력

# null safety

! - null checker << null이면 중단

? - nullable << null이 들어올 수 있음

?? - Nullish Coalescing << 앞이 null이면 뒤의 값 사용

[[Flutter] 플러터 null safty와 ? ! 이해 (물음표, 느낌표)](https://son50math.tistory.com/88)

[Double Exclamation Mark(느낌표 두개)](https://daramji-joa.tistory.com/7)

[[Dart]다트(3) - 특이한 연산자](https://sneakstarberry.github.io/posts/dart03-operand/)

# Callback function

typedef DoubleCallback = void funcion(double);

[Flutter - Callback - 1](https://velog.io/@qlr222/Flutter-Callback-1)
