# 볼링
## 프로젝트 소개
NextStep에서 클린코드를 수강하며 만든 프로젝트입니다. 최종 소스 코드를 보시고 싶으시다면 master 대신 Step 1 branch를 확인해주세요

## 프로젝트 발전 단계별 branch 링크
Step1 https://github.com/JoyDaheeCha/java-bowling/tree/step1

# 볼링 게임 step1 TODO

## 질문 삭제
- [X] 데이터의 상태값만 변경
- [ ] 질문 삭제 가능 여부
    - [X] 로그인 사용자 = 질문자
        - [X] 답변 없을 때: 삭제 가능
        - [X] 답변 있을 때
            - [X] 질문자 != 답변자: 삭제 불가 (exception)
            - [X] 질문자 = 답변자: 삭제 가능
- [X] 로그인 사용자 != 질문자: exception

## 답변 삭제

- [X] 데이터의 상태값만 변경
- [X] 답변 삭제 가능 여부
    - [X] 질문자 != 답변자 : 삭제 불가
    - [X] 질문자 = 답변자 : 삭제 가능

- [X] Delete History 남기기
    - [X] 질문
    - [X] 답변

## 서비스 메서드 내 로직을 도메인으로

- [X] deleteQuestion 이동 완료

## Answers

- [X] 추가
- [X] 삭제
