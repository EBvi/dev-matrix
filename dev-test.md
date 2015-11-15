## 신입 사원 웹 개발자 필기 시험 문제

- 통계 데이터는 5%를 끊은 근사치입니다.
- 제한시간은 20분이며 지원자가 시간이 더 필요하다고 하면 최대 10분까지 더 늘렸습니다.

---

### Java로 hello world를 출력하는 main 메소드를 작성하시오.
> 정답률 30%

- main 메소드를 작성할 줄 아는 것은 이 분야에 발을 담그는 것에 대한 최소한의 예의(?)라고 생각해서 출제
- 약간의 오타는 감안할 수 있으나 public static void main은 절대로 틀리면 안 됨

---

### alz로 압축을 하거나, hwp로 문서를 작성하여 외국에 전송하면 안 되는 이유를 설명하시오.
>정답률 90%

- 외국에서 사용하지 않는다 혹은 표준이 아니라는 등의 답변을 쓰면 정답으로 인정

---
### for문을 사용하여 1에서 10까지의 합을 구하는 프로그램을 작성하시오. (main 메소드 불필요)
> 정답률 60%

- 기초적인 문법을 숙지하고 있는지 평가
- 대부분 부호를 잘못 써서 틀림 (1에서 10까지 더하라면 0<=10 또는 0<11로 써야 함)
- 변수 선언을 하지 않아도 정답으로 인정함

---

### 다음은 javadoc의 String.replaceAll 메소드에 대한 설명이다. 우리말로 해석하시오.
> 정답률 15%

Replaces each substring of this string that matches the given regular expression with the given replacement.

- 영어로 된 문서를 보고 이해할 수 있는지 평가
- 정규표현식의 번역을 몰라서 regular expression으로 그대로 둬도 정답으로 인정

---
### 리눅스를 설치해보신 적이 있습니까? 설치해 본 제품명을 기술하시오. 또한 어떠한 용도로 사용해 보았는지 기술하시오.
> 정답률 40%

- 종류와 버전을 불문하고 리눅스를 설치해본 경험이 있다고 하면 정답으로 인정
- OS 경험도 점수로 인정하는 편이 좋다고 생각했음

---

### 다음 빈칸을 채우시오.

(-----------------------) is a programming paradigm that uses "objects" – data structures consisting of data fields and methods together with their interactions – to design applications and computer programs. Programming techniques may include features such as data abstraction, encapsulation,
modularity, polymorphism, and inheritance. Many modern programming languages now support (-----------------------)

> 정답률 20%

- 한글로 "객체지향프로그래밍" 또는 OOP로 쓰면 정답으로 인정
- 두 항목에 다른 대답을 쓰는 경우도 있었는데 그 경우 부분 점수를 인정

---

### 다음 주어진 div의 클래스를 정의하시오.

##### - 너비가 250px이고 높이가 300px이며, 배경색이 검은색인 hello 클래스

``` html
<div class="hello">안녕하세요</div>
<style type="text/css">
.hello {



}
</style>
```

> 정답률 25%

- 기초적인 CSS 문법을 알고 있는지 평가
- background나 background-color 모두 정답

---

### 세션과 쿠키의 차이점에 대해 간략히 설명하시오.

> 정답률 30%

- 서버와 클라이언트 차이에 대해 서술하면 정답으로 인정
- 라이프 사이클에 대한 설명이 있다면 금상첨화
- 세션이 보안적으로 안전하다는 데에는 이견이 있으나, 여기서는 그렇게 기술해도 정답으로 인정

---

### 다음 소스코드를 읽고 무엇을 하는 프로그램인지 서술하시오.


``` java
char[] arr = someString.toCharArray(); // 해당 문자열로부터 캐릭터 배열을 선언한다
StringBuffer sb = new StringBuffer();
int size = 0;
for(char c : arr) {
    size += (c > 255) ? 2 : 1; // 조건에 따라 2 또는 1을 증가시킨다
    sb.append(c);
    if(size >= 80) {
        break;
    }
}
return sb.toString();
```

> 정답률 10%

- char의 타입을 이해하고 있는지 평가
- 남이 짠 소스 코드를 읽을 수 있는지를 평가 (코드 리딩)
- 이 소스는 온전한 소스가 아니나 일부러 간략하게 만들었음

---

### 다음 javascript 소스코드가 어떻게 동작할지 서술하시오.
``` javascript
function f() {
    for ( var i = 0; i < 3; i++ ) {
        setTimeout( function() {
            alert( i );
        }, 1000);
    }
}
f(); // f를 실행한다
```



> 정답률 0%

- timer나 클로저를 이해하고 있는지 평가
- 이 문제는 일종의 덤임(신입 레벨에서 맞출 수 있는 사람이 있으리라고 기대하지 않음)
- 기대하지 않았다고 해도 이 문제를 대하는 태도와 답변에서 지원자의 많은 부분을 엿볼 수 있었음

---

### 다음 조건을 만족하는 SQL 질의문을 작성하시오.
사원번호(emp.seq), 이름(emp.name), 부서명(dept.name) 컬럼이 매핑되며, **모든 사원**이 전부 출력되어야 함

```
emp 테이블
------------------
seq | name | dept_seq
1 | 홍길동 | 2
2 | 죠나단 | 1
3 | 죠스타 | null

dept 테이블
------------------
seq | name
1 | 개발부
2 | 운영부
```

> 정답률 10%

- left outer join 문법을 이해하고 있는지 평가

## 지원자에 대한 통계

#### 성별
- 남 : 73%
- 여 : 27%

#### 전공
- 전공자 : 64% (컴퓨터공학, 소프트웨어학과, 전자공학부)
- 비전공자 : 36%

#### 나이
- 최소 : 23
- 평균 : 27.7
- 최대 : 30

#### 점수
- 최소 : 1
- 평균 : 3.4
- 최대 : 8
