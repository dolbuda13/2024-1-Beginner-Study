2주차
==============================
#github의 Fork/star
----------------------
>*Fork: 다른 사용자의 레포지토리를 나에게 복사 >> 독립적으로 수정, 관리 가능
>*Star: 관심 있는 레포지토리 or 프로젝트에 star을 달아 표시 (=북마크)

#Issue
--------------
>레포지토리에서 작업 계획, 토론 및 추적을 위해 활용

#Branch
--------------
>*기존 브랜치(main)에서 분기되어 생성되는 별도의 작업 공간
>이름생성 규칙: "type/<issue 번호>-<간략한 설명>"
>실습에서는 docs/3-readme
>fork와 달리 같은 레포지토리에 생성됨

#Pull Request
--------------
>분기된 Branch를 다시 병합하기 위한 절차
>새로운 변경을 제안하거나 병합 시 발생하는 충돌을 해겲
>Merge에 앞서 코드리뷰

#Merge
---------------
>Merge에는 3가지 옵션이 존재
>>1. Merge Commit
>>>두 브랜치를 공통 부모로 하는 새로운 commit 'E'를 만듦
>>>Feature branch의 A, B, C의 커밋이 그대로 main 브랜치로 병합
>>2. Squash and Merge
>>>Feature branch의 A, B, C의 커밋을 squash => 하나의 커밋으로 main 브랜치로 병합
>>3. Rebase and Merge
>>>Feature branch의 A, B, C 커밋의 base를 재설정 => 모두 새로운 main 커밋으로 변경
>>>commit hash가 변경됨
>>>>commit hash란?
>>>>commit의 식별을 위해 사용하는 40자 길이의 16진수
>>>>중복 확률은 2의 80제곱 분의 1
>>>>SHA-1 해시 함수를 사용
>>>무수한 충돌 가능, 주의

#실습
--------------
>1. issue 만들기
>2. Branch 만들기
>> git branch (현재 브랜치 확인하기)
>> git branch -a (모든 브랜치 확인하기)
>> git branch "브랜치 이름" (브랜치 생성하기)
>> git branch -D "브랜치 이름" (브랜치 삭제하기)
>> git checkout "브랜치 이름" (브랜치 이동하기)
>> git checkout -b "브랜치 이름" (브랜치 생성 후 이동하기)
>3. README.md 만들기
>4. Commit and Push
>5. Pull Request 만들기
>6. Merge

과제 링크
https://github.com/dolbuda13/2024-1-Beginner-Study/pull/2
<https://github.com/dolbuda13/2024-1-Beginner-Study/pull/2>
---------

--------
