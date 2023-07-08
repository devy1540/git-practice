# Scenario

1. 개발자1과 개발자2가 존재합니다.
2. 개발자1은 `rebase-master`에서 `rebase-featured-001` 작업 브랜치를 생성합니다.
3. 개발자1은 `rebase-featured-001`에서 작업을 실행합니다.
4. 개발자2는 `rebase-master`에서 `rebase-featured-002` 작업 브랜치를 생성합니다.
5. 개발자2는 `rebase-featured-002`에서 작업을 실행합니다.
6. 개발자2는 작업한 내역을 `rebase-master`에 merge를 합니다.
7. 개발자1은 `rebase-master`의 코드를 받아서 rebase를 진행합니다.


