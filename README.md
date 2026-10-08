# 11주차 · JavaScript 코어 객체 활용

Array, String, Math 등 주요 객체 다루기 · 함수와 객체

- 과목: 한신대학교 웹프로그래밍 (AS006-E)
- 주차 강의안: https://hs-web.dreamitbiz.com/weeks/11

## 여는 방법

1. 압축을 풉니다.
2. VS Code 에서 **폴더째로** 엽니다 (파일 → 폴더 열기).
3. `.html` 파일을 더블클릭하면 브라우저에서 바로 열립니다.
   VS Code 라면 Live Server 확장을 쓰는 편이 편합니다 — 저장하면 화면이 바로 바뀝니다.
4. 고쳐 보고, 저장하고, 브라우저를 새로고침(F5)하세요.

**고쳐 보라고 드리는 파일입니다.** 망가뜨려도 괜찮습니다 — 다시 받으면 됩니다.

## 학습 목표

- 함수를 만들어 반복되는 코드를 묶고 재사용할 수 있다.
- 화살표 함수를 읽고 쓸 수 있다.
- Array 메서드(map·filter·find·reduce)를 상황에 맞게 골라 쓸 수 있다.
- String·Math 등 내장 객체의 주요 메서드를 활용할 수 있다.
- 객체로 여러 값을 하나로 묶고, 배열과 조합해 자료를 다룰 수 있다.
- 값이 복사되는 것과 참조가 복사되는 것의 차이를 설명할 수 있다.

## 이번 주 낱말

function · 화살표 함수 · return · 스코프 · Array · map/filter/find/reduce · String · Math · 객체 · 구조 분해 · JSON

## 담긴 파일

### examples/ — 강의안에 나온 예제 22개

- `examples/01.html` — 함수 만들고 쓰기
- `examples/02.html` — 요즘 더 많이 쓰는 모양
- `examples/03.html` — 값이 안 넘어왔을 때
- `examples/04.html` — 중괄호 밖에서는 안 보입니다
- `examples/05.html` — 기본
- `examples/06.html` — 추가·제거
- `examples/07.html` — map — 각각을 바꿔 새 배열
- `examples/08.html` — filter — 조건에 맞는 것만
- `examples/09.html` — find — 첫 하나만
- `examples/10.html` — reduce — 하나로 합치기
- `examples/11.html` — sort — ⚠ 함정이 있습니다
- `examples/12.html` — 메서드 이어 쓰기 (체이닝)
- `examples/13.html` — 만들고 꺼내 쓰기
- `examples/14.html` — 추가·수정·삭제·확인
- `examples/15.html` — 자주 보게 될 문법입니다
- `examples/16.html` — ...  세 점
- `examples/17.html` — 가장 헷갈리는 지점입니다
- `examples/18.html` — 거의 모든 웹 데이터가 이 모양입니다
- `examples/19.html` — 객체 ↔ 문자열
- `examples/20.html` — 자주 쓰는 문자열 메서드
- `examples/21.html` — Math는 new 없이 바로 씁니다
- `examples/22.html` — 변환과 검사

### lab/ — 실습 4개

- `lab/lab1.html` — 실습 1 · 기본
- `lab/lab2.html` — 실습 2 · 기본
- `lab/lab3.html` — 실습 3 · 응용
- `lab/lab4.html` — 실습 4 · 심화

문제와 힌트는 각 실습 파일 맨 위 주석에 그대로 적어 두었습니다.
모범답안은 `lab/answer/` 에 있습니다. **먼저 스스로 해 본 뒤에** 열어 보세요.

## 다 만들었으면

실습 결과를 패들릿에 올려 자랑해 주세요.
주차 강의안 페이지 **맨 위**의 [11주차 실습 자랑하기] 단추로 들어갑니다.

> ⚠ 패들릿은 **서로 보고 배우는 자랑·질문용**입니다. 성적과는 관계가 없습니다.
> 성적에 들어가는 **실습 과제는 학교 LMS에 제출**합니다 — https://lms.hs.ac.kr/

- 실습 결과(화면 캡처) → 「11주차 실습 제출」 칸
- 막히거나 안 되는 것 → 「11주차 질문·막힌 곳」 칸

https://padlet.com/dreamitbiz/hs2605
