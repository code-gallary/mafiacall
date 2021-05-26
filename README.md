# Mafia call

소규모(최대 8인) 화상회의 앱

## Docs
<details>
<summary>펼치기</summary>

- Feature list
- ERD
- Skill spec detail
  - Web
  - Server
  - App
- Rules 
  - Issue based development
    > 매 주 무엇을 할 것인가 무조건 공유
    1. 이슈 작성은 전주/전날 미리 작성
    2. 매일 이슈 변동 및 작업 일정 공유
    3. 질문도 이슈로 태그 걸어서 추가
    4. 이슈 등록 시 프로젝트에 추가하기
     
  - Commit convention:
    ```
    docs #11: Update README.md 
    docs #noissue: fix README 이슈가 없을 때
    메시지 헤더는 무엇을 했는지(How, 한줄 요약)
    메시지 본문은 왜 했는지(Why)
    무엇을 했는지는 생략, 왜냐하면 커밋 로그에서 찾을 수 있으므로
    ```
    Type | Content
    :---: | :---:
    feat | 새로운 기능을 추가 했을 때
    fix | 버그 수정했을 때
    refactor | 코드 스타일이나 구조 리팩토링했을 때
    docs | 문서나 wiki 수정 했을 때
    style | 스타일이나 컴포넌트, 페이지 레이아웃을 수정 했을 때
    test | 테스트 코드에 대한 수정, 리팩토링 했을 때
    chore | 빌드스크립트나 환경변수 같은 기타 수정
    resource | 이미지나 svg같은 코드와 상관없는 리소스를 수정했을 때

  - Code convention:
    - Javascript: [eslint - airbnb](https://github.com/airbnb/javascript#in-the-wild)
    - Java/Kotlin(Android): [Android lint](https://developer.android.com/studio/write/lint)
  - Branch rule: [Github flow](https://guides.github.com/introduction/flow/)
    > 예시
    1. **fork한다.**
    2. 내 레파지토리에서 clone한다.
    3. 테스트 작성하고 개발하고 작은 단위 커밋후 푸쉬한다.
    4. 완료되고 PR을 한다.
    5. Tool 검증과 리뷰가 끝나면 main repo의 main branch에 merge한다.
   
</details>

## Demo
[링크](#)

## Features
<details>
<summary>펼치기</summary>

### 필수 구현 기능
- 인증(호스트 로그인/ 회원가입)
- 화상회의
- 실시간 채팅
- 파일 공유 및 전송
### 선택 구현 기능(Optinal)
- 비디오 / 오디오 선택모드
- 채팅 허용 여부
- 화면 스타일 전환
- 최대인원 설정
- 결제(Boost, dynamic emoji)
### 선택 구현 기능(Optinal of Optional)
- 결제(멤버쉽)  
</details>

## Tech stack
## Architecture
## History
