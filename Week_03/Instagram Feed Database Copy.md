# Instagram Feed Database Copy

## ERD 설계

![image](https://user-images.githubusercontent.com/43658658/132510879-06e0f7e9-c373-4580-9941-f3c2b9f5d135.png)

테이블은 크게 4개로 생각해 볼 수 있습니다.

1. User : 인스타의 유저에 관한 정보가 담기는 테이블입니다.
2. Feed : 피드에 들어갈 컨텐츠 정보가 담기는 테이블입니다.
3. clickLike : '좋아요'를 누른 회원의 정보가 담기는 테이블입니다.
4. Reply : 댓글과 관련한 정보가 담기는 테이블입니다.

타임라인에 있는 많은 피드들 중 하나의 피드를 클릭했을 때 그 피드에 대한 정보를 출력하는 SQL문을 작성하겠습니다.