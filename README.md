# 👊 주먹구구 팀

> 주먹구구 팀을 소개합니다.

## 🚴‍♂️ Teams

### 김민수

전공: 소프트웨어학부 다중전공  
학번: 2016001694

#### Contact

email: zlemzlem5656@naver.com

### 박찬혁

전공: 소프트웨어학부 다중전공(기계공학과)
학번: 2016005387

#### Contact

email: pgg6713@gmail.com
github : [박찬혁 깃허브](https://github.com/ChanhyukPark-Tech)

### 김승환

전공 : 신산업소프트웨어학과 융합전공  
학번 : 2016001221

### contact

email : seunghwan9703@gmail.com

### 김다예

전공: 소프트웨어학부 소프트웨어전공
학번: 2020064448

#### Contact

email: kimdaye77@naver.com
github : [김다예 깃허브](https://github.com/kimdaye77)

## Commit Conventions

참고자료: [좋은 git 커밋 메시지를 작성하기 위한 8가지 약속](https://djkeh.github.io/articles/How-to-write-a-git-commit-message-kor/)

- 커밋 메세지는 영문으로 작성한다.
- 제목은 명령조로 작성한다.
- 제목과 본문은 분리해서 작성한다.
- 본문은 무엇을 보다 `어떻게` 와 `왜` 에 집중해서 작성한다.

### Convention for Jira

- task 하나 : 하나의 브랜치 = 1 : 1 로 작업을 한다.
- task 의 하위 이슈(하위 작업)가 생길 경우 브랜치는 생성하지 않는다. (미정)
- 커밋 메세지 첫 줄 컨벤션은 다음과 같다.
  - [헤더] [SETB-{issue number}] 커밋 메세지
  - 헤더 종류는 다음과 같다.
    - add: 기능 구현
    - fix: 코드/버그 수정
    - hofix: hotfix 브랜치에서 생성되는 모든 커밋 헤더
    - docs: 문서 작업
    - PR: PR 생성할 때 붙여주는 헤더
- 브랜치 네이밍 컨벤션
  - SETB-{issue number}/{branch name}-{work feature}
- test
