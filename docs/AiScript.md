# AiScript

# 1. 개요

$[x2 :aiscript_ai::aiscript_sc::aiscript_ri::aiscript_pt:]

> AiScript는, JavaScript상에서 동작하는 경량 스크립트 언어입니다.

**아이스크립트**.

# 2. 주요 구문

* [연산자](연산자(AiScript).md)
* [if문](if문(AiScript).md)
* [for문](for문(AiScript).md)
* [each문](each문(AiScript).md)
* [loop문](loop문(AiScript).md)

```
var a = 0

// Error
// while (a < 5) {
//   a = a + 1
// }

loop {
  a = a + 1
  if (!(a < 5)) { break }
}

<: `{a}`  // 5
```

# 3. 내장 함수

## 3.1 기본 내장 함수

## 3.2 Misskey에서 사용할 수 있는 내장 함수 및 변수

* [USER_ID](AS_USER_ID(AiScript).md)
* [USER_NAME](AS_USER_NAME(AiScript).md)
* [USER_USERNAME](USER_USERNAME(AiScript).md)
* [CUSTOM_EMOJI](CUSTOM_EMOJI(AiScript).md)

# 4. 관련 문서

* [PiScript](PiScript.md) : 아이스크립트의 확장판. [피치타르트](피치타르트.md)에서만 사용할 수 있다.
