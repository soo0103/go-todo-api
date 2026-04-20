# Go Todo API

이 프로젝트는 Tucker의 Go 언어 프로그래밍을 기반으로
Go 언어로 REST API 서버를 구현해보는 학습용 프로젝트입니다.


## 프로젝트 소개

Go의 기본 웹 서버 구조와 REST API 설계를 이해하기 위해
간단한 Todo List API를 구현했습니다.

* net/http 기반 서버
* gorilla/mux 라우팅
* in-memory map 데이터 저장
* JSON 요청/응답 처리
* middleware (negroni)
* 정렬 기능 구현

## 사용 기술

* Go
* net/http
* gorilla/mux
* unrolled/render
* negroni
* encoding/json

## 주요 기능

* Todo 생성 (POST /todos)
* Todo 조회 (GET /todos)
* Todo 수정 (PUT /todos/{id})
* Todo 삭제 (DELETE /todos/{id})

## 프로젝트 구조

```id="a1"
todo
├── main.go
├── public # 정적 파일
├── go.mod
└── README.md
```

## 실행 방법

```bash id="a2"
go mod tidy
go run main.go
```

서버 주소:

```id="a3"
http://localhost:3000
```
