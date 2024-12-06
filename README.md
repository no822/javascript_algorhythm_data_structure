서적 <자바스크립트로 하는 자료구조와 알고리즘> 학습 레포지토리

## 목차

### 1장. 빅오 표기법

- 빅오 표기법 기초
  - 일반적인 예
- 빅오 표기법 규칙
  - 계수 법칙: "상수를 제거하라"
  - 합의 법칙: "빅오를 더하라"
  - 곱의 법칙: "빅오를 곱하라"
  - 다항 법칙: "빅오의 k승"
- 요약
- 연습 문제
  - 정답

### 2장. 자바스크립트의 독특한 특징

- 자바스크립트 범위
  - 전역 선언: 전역 범위
  - var를 사용해 선언하기: 함수 범위
  - let을 활용한 선언: 블록 범위
- 등가와 형
  - 변수형
  - 참/거짓 확인
  - === 대 ==
  - 객체
- 요약

### 3장. 자바스크립트 숫자

- 숫자 체계
- 자바스크립트 숫자 객체
  - 정수 반올림
  - Number.EPSILON
  - 최대치
  - 최소치
  - 무한
  - 크기 순서
  - 숫자 알고리즘
  - 소인수 분해
- 무작위 수 생성기
- 연습 문제
- 요약

### 4장. 자바스크립트 문자열

- 자바스크립트 문자열 기본
  - 문자열 접근
  - 문자열 비교
  - 문자열 검색
  - 문자열 분해
  - 문자열 바꾸기
- 정규 표현식
  - 기본 정규 표현식
  - 자주 사용하는 정규 표현식
  - 숫자를 포함하는 문자
  - 숫자만 포함하는 문자
  - 부동소수점 문자
  - 숫자와 알파벳만을 포함하는 문자
  - 질의 문자열
- 인코딩
- Base64 인코딩
- 문자열 단축
- 암호화
  - RSA 암호화
- 요약

### 5장. 자바스크립트 배열

- 배열 소개
  - 삽입
  - 삭제
  - 접근
- 반복
  - for (변수; 조건; 수정)
  - for ( in )
  - for ( of )
  - forEach( )
- 도움 함수
  - slice(begin,end)
  - splice(begin,size,element1,element2)
  - concat( )
  - length 속성
  - 전개 연산자
- 연습 문제
- 자바스크립트 함수형 배열 메소드
  - map
  - filter
  - reduce
- 다차원 배열
- 연습 문제
- 요약

### 6장. 자바스크립트 객체

- 자바스크립트 객체 속성
  - 프로토타입 활용 상속
- 생성자와 변수
- 요약
- 연습 문제

### 7장. 자바스크립트 메모리 관리

- 메모리 누수
  - 객체에 대한 참조
  - DOM 메모리 누수
  - window 전역 객체
  - 객체 참조 제한하기
  - delete 연산자
- 요약
- 연습 문제

### 8장. 재귀

- 재귀 소개
- 재귀의 규칙
  - 기저 조건
  - 분할 정복 방식
  - 대표적인 예: 피보나치 수열
  - 피보나치 수열: 꼬리 재귀
  - 파스칼의 삼각형
- 재귀의 빅오 분석
  - 점화식
  - 마스터 정리
- 재귀 호출 스택 메모리
- 요약
- 연습 문제

### 9장. 집합

- 집합 소개
- 집합 연산
  - 삽입
  - 삭제
  - 포함
- 기타 유틸리티 함수
  - 교집합
  - 상위 집합 여부 확인
  - 합집합
  - 차집합
- 요약
- 연습 문제

### 10장. 검색과 정렬

- 검색
  - 선형 검색
  - 이진 검색
- 정렬
  - 거품 정렬
  - 선택 정렬
  - 삽입 정렬
  - 빠른 정렬
  - 빠른 선택
  - 병합 정렬
  - 계수 정렬
  - 자바스크립트 내장 정렬
- 요약
- 연습 문제

### 11장. 해시 테이블

- 해시 테이블 소개
- 해싱 기법
  - 소수 해싱
  - 탐사
  - 재해싱/이중 해싱
- 해시 테이블 구현
  - 선형 탐사 사용하기
  - 이차 탐사 사용하기
  - 선형 탐사를 활용해 이중 해싱 사용하기
- 요약

### 12장. 스택과 큐

- 스택
  - 들여다보기
  - 삽입
  - 삭제
  - 접근
  - 검색
- 큐
  - 들여다보기
  - 삽입
  - 삭제
  - 접근
  - 검색
- 요약
- 연습 문제

### 13장. 연결 리스트

- 단일 연결 리스트
  - 삽입
  - 값에 의한 삭제
  - 헤드 항목 삭제
  - 검색
- 이중 연결 리스트
  - 헤드에 항목 삽입하기
  - 테일에 항목 삽입하기
  - 헤드의 항목 삭제하기
  - 테일의 항목 삭제하기
  - 검색
- 요약
- 연습 문제

### 14장. 캐싱

- 캐싱 이해하기
- LFU 캐싱
- LRU 캐싱
- 요약

### 15장. 트리

- 일반적인 트리 구조
- 이진 트리
- 트리 순회
  - 선순위 순회
  - 중순위 순회
  - 후순위 순회
  - 단계순위 순회
  - 트리 순회 요약
- 이진 검색 트리
  - 삽입
  - 삭제
  - 검색
- AVL 트리
  - 단일 회전
  - 오른쪽 회전
  - 이중 회전
  - 트리 균형 잡기
  - 삽입
  - AVL 트리 예제 종합
- 요약
- 연습 문제

### 16장. 힙

- 힙에 대한 이해
  - 최대 힙
  - 최소 힙
- 이진 힙 배열 인덱스 구조
  - 삼투: 위로 아래로 이동
  - 삼투 구현하기
  - 최대 힙 예
- 최소 힙 구현 완성
- 최대 힙 구현 완성
- 힙 정렬
  - 오름차순 정렬(최소 힙)
  - 내림차순 정렬(최대 힙)
- 요약
- 연습 문제

### 17장. 그래프

- 그래프 기본
- 무지향성 그래프
  - 간선과 정점 추가하기
  - 간선과 정점 삭제하기
- 지향성 그래프
- 그래프 순회
  - 너비 우선 검색
  - 깊이 우선 검색
- 가중치가 있는 그래프와 최단 경로
  - 가중치가 있는 간선을 지닌 그래프
  - 다익스트라의 알고리즘: 최단 경로
- 위상 정렬
- 요약

### 18장. 고급 문자열

- 트라이(접두사 트리)
- 보이어-무어 문자열 검색
- 커누스-모리스-플랫 문자열 검색
- 라빈-카프 검색
  - 라빈 지문
  - 실생활 적용 예
- 요약

### 19장. 동적 프로그래밍

- 동적 프로그래밍의 필요성
- 동적 프로그래밍의 규칙
  - 중복 부분 문제
  - 최적 부분 구조
  - 예: 걸음 수를 채우는 방법
- 대표적인 동적 프로그래밍 예
  - 배낭 문제 알고리즘
  - 최장 공통 부분 수열 알고리즘
  - 동전 교환 알고리즘
  - 편집 거리 알고리즘
- 요약

### 20장. 비트 조작

- 비트 연산자
  - AND
  - OR
  - XOR
  - NOT
  - 왼쪽 이동
  - 오른쪽 이동
  - 오른쪽 이동 후 0으로 채우기
- 숫자 연산
  - 덧셈
  - 뺄셈
  - 곱셈
  - 나눗셈
- 요약
