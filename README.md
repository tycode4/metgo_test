# metGo (맺고)
![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d04675fa-b8b5-456e-9513-ada606fff2a8/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d04675fa-b8b5-456e-9513-ada606fff2a8/Untitled.png)

# metGo 프로젝트 Front-end / Back-end 소개
* Soomgo 웹사이트의 (유저-고수 매칭) 기능을 모티브로 제작한 프로젝트입니다.
* 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인 및 기능의 기획 부분만 클론했습니다.
* 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

# 개발 인원 및 기간
* 개발기간 : 2021/7/19 ~ 2021/7/30
* 개발 인원 :
👉  Front-end : 성정준, 이윤경, 이의연 
👉  Back-end : 김태영, 최준영, 이신재

# 프로젝트 선정이유
* 깔끔한 레이아웃이 매력적이고 UI 기능 개선이 가능하다 생각하여 선정하였습니다.
* 다양한 React의 라이브러리를 접목하여 사용해볼 수 있습니다.
* 유저 매칭 및 필터링 등 실제 서비스에서 적용할 수 있는 기능들을 구현해 볼 수 있습니다.
* 다양한 카테고리 및 서비스에 유저가 원하는 고수를 매칭시켜주는 기능이 매력적입니다.
* 해당 db를 바탕으로 유저 및 고수 활동 분석등의 기능을 구현할 수 있습니다.

# 데모 영상
https://youtu.be/S5pPqUqrppY

# 적용 기술 및 구현 기능
## 적용 기술
* Front-End : React.js, sass, react-modal
* Back-End : Python, Django web framework,  PyJWT, Bcrypt, My SQL, AqueryTool, AWS(EC2, RDS, S3), Docker, Kakao Login Api

## 협업 도구
* Slack
* Git + GitHub
* Trello를 이용, 일정관리 및 작업 현황 확인

## 구현 기능
💻  Back-end

### **<태영>**
### User
- 회원가입 뷰 (패스워드 해쉬, 벨리데이션, 토큰)
- 로그인 뷰 (패스워드 검증(해쉬), 토큰)
- 서치 뷰 (쿼리파라미터 이용한 검색어 자동완성)
- 토큰 검사 데코레이터

### Like
- StatusView (먹고싶어요, 먹어봤어요)
- LikeView (댓글에 좋아요)

### Comment
- 댓글 뷰 (작성, 읽기, 수정, 삭제)

### **<신재>**
### Product
- 상품 뷰 (쿼리파라미터 이용한 카테고리 필터링, 별점 높은 순으로 정렬)
- 상품 프라이빗 뷰 (로그인한 유저만 접근, 페이지네이션, 카테고리 필터링)
- 상품 상세 뷰 (상세 정보, 해당 상품 다른 이미지들)

### Rating
- 별점 뷰 (읽기, 작성, 수정, 삭제)
- 별점 그래프 뷰 (해당 상품에 대한 별점 모두 읽기)
- 별점 총 카운트 뷰 (모~든 별점 카운트)

### **<준영>**
### User

- 회원가입 뷰 (패스워드 해쉬, 벨리데이션, 토큰)
- 로그인 뷰 (패스워드 검증(해쉬), 토큰)
- 서치 뷰 (쿼리파라미터 이용한 검색어 자동완성)
- 토큰 검사 데코레이터

### Like
- StatusView (먹고싶어요, 먹어봤어요)
- LikeView (댓글에 좋아요)

### Comment
- 리글 뷰 (작성, 읽기, 수정, 삭제)

# Reference
- 이 프로젝트는 숨고 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
