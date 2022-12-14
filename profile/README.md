<a name="Top"></a>

# 일상의 방탈출

| Frontend                                                         | Backend                                                         |
| ---------------------------------------------------------------- | --------------------------------------------------------------- |
| [:detective:](https://github.com/sherlock-escape/sherlock_front) | [:detective:](https://github.com/sherlock-escape/Sherlock_Back) |


## 📑 목차

1. [🚪 프로젝트 소개](#-프로젝트-소개)
2. [✨ 주요 기능](#-주요-기능)
3. [💻 기술 스택](#-기술-스택)
4. [🔫 트러블 슈팅](#-트러블-슈팅)
5. [🧑‍🤝‍🧑 팀원 소개](#-팀원-소개)
6. [📝 라이센스](#-라이센스)
7. [🙏 도움주신분들 | Special Thanks](#-도움주신분들--special-thanks)

## 🚪 프로젝트 소개
![KakaoTalk_Photo_2022-12-14-21-31-26](https://user-images.githubusercontent.com/109974940/207609115-5527fcaf-8c71-4c18-83a5-138c8671c20b.jpeg)

[:globe_with_meridians:]()

> 지루한 일상으로부터의 일탈을 꿈꾸는 <br/>
> 방탈출 사이트 일상의 탈출입니다.

![](./src/asset/test-img.webp)

프로젝트를 소개하는 내용입니다

<p align="right">(<a href="#Top">맨 위로</a>)</p>

## ✨ 주요 기능
- 방탈출 업체와 테마의 정보를 한번에 모아볼 수 있습니다.
- 원하는 방탈출 테마의 조건으로 검색하고 평점순,리뷰순 등으로 정렬해서 볼 수 있습니다.
- 하고 싶은 테마를 찾았다면 예약사이트로 바로 연결할 수 있습니다.
- 방탈출을 하고 해당 테마의 리뷰를 남기면 성공횟수와 실패횟수로 뱃지를 획득할 수 있습니다.
- 마음에 드는 방탈출 업체와 테마는 찜해두고 마이페이지에서 모아볼 수 있습니다.


<p align="right">(<a href="#Top">맨 위로</a>)</p>

## 💻 기술 스택

✔️ Front-end

<img src="https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=React&logoColor=white"> <img src="https://img.shields.io/badge/styled_components-4.4.2-DB7093?style=for-the-badge&logo=styled-components&logoColor=white"> <img src="https://img.shields.io/badge/Axios-1.1.3-5A29E4?style=for-the-badge&logo=Axios&logoColor=white"> <img src="https://img.shields.io/badge/React_Query-4.14.5-FF4154?style=for-the-badge&logo=React-Query&logoColor=white"> <img src="https://img.shields.io/badge/React_Hook_Form-7.39.1-EC5990?style=for-the-badge&logo=React-Hook-Form&logoColor=white"> <img src="https://img.shields.io/badge/date_fns-2.29.3-5F0733?style=for-the-badge&logo=date_fns&logoColor=white"> <img src="https://img.shields.io/badge/React_Router_Dom-6.4.3-CA4245?style=for-the-badge&logo=React-Router&logoColor=white"> <img src="https://img.shields.io/badge/yup-0.32.11-6048C3?style=for-the-badge&logo=yup&logoColor=white"> <img src="https://img.shields.io/badge/rc_slider-13.1.1-E4637C?style=for-the-badge&logo=Slides&logoColor=white"> <img src="https://img.shields.io/badge/react_infinite_scroller-1.2.6-000000?style=for-the-badge&logo=Infiniti&logoColor=white"> <img src="https://img.shields.io/badge/react_kakao_maps_sdk-1.1.5-FFCD00?style=for-the-badge&logo=Kakao&logoColor=white"> <img src="https://img.shields.io/badge/react_slick-0.29.0-FF880F?style=for-the-badge&logo=slickpic&logoColor=white">


✔ DevOps

✔️ Back-end 

<img src="https://img.shields.io/badge/Spring-2.7.5-6DB33F?style=for-the-badge&logo=Spring&logoColor=white" > <img src="https://img.shields.io/badge/Spring_Boot-2.7.5-6DB33F?style=for-the-badge&logo=Spring-Boot&logoColor=white"> <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=Spring%20Security&logoColor=white"> <img src="https://img.shields.io/badge/Amazon%20ECS-FF9900?style=for-the-badge&logo=Amazon%20ECS&logoColor=white"> <img src="https://img.shields.io/badge/Amazon%20RDS-527FFF?style=for-the-badge&logo=Amazon%20RDS&logoColor=white"> <img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white"> <img src="https://img.shields.io/badge/Amazon%20AWS-232F3E?style=for-the-badge&logo=Amazon%20AWS&logoColor=white"> <img src="https://img.shields.io/badge/QueryDsl-1.0.10-2962ff?style=for-the-badge&logo=QueryDsl&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/JSON%20Web%20Tokens-0.11.2-000000?style=for-the-badge&logo=JSON%20Web%20Tokens&logoColor=white"> <img src="https://img.shields.io/badge/GitHub Actions-181717?style=for-the-badge&logo=GitHub-Actions&logoColor=white" >







<p align="right">(<a href="#Top">맨 위로</a>)</p>

## 🔫 트러블 슈팅

<details>
<summary>쿼리 성능 개선</summary>
<div markdown="1">

#### 🧐 요구사항

- 사이트를 이용하는 user의 username을 이용해서 user의 정보, 성공횟수, 실패횟수를 구해야한다. 

- 내가 작성한 후기 조회를 조회 한다.

- 우리 사이트가 가지고 있는 칭호를 조회한다. 
 
- 해당하는 테마의 후기를 조회한다.

#### 💣 문제상황

- 하나의 API 안에서 여러 개의 Entity를 조회하려고 할 때 다수의 N + 1문제가 발생한다.
  
- 관련된 조회할 때 불필요하게 select 문이 계속 실행되어서 log에 select문이 많이 찍히는 것을 발견함

#### 💡해결방안

1. 기본적으로 성능에 관한 문제는 jpql fetch join을 사용하면 된다는 것을 알았고, query to dto를 사용하면 유의미하지만 이 또한 성능개선이 된다는것을 알게되었다.
   jpql fetch join을 사용하게 되면 select문이 한번만 실행되었고 query to dto를 사용해서 service로직 또한 간결해졌다. 
   
2. Querydsl의  projections 기능을 이용해서 Entity 전체를 불러오는 것이 아닌 필요한 데이터만 불러오게 였더니 성능개선의 효과가 (57ms → 46ms) 있었고 
   dto를 repository에서 바로 반환하기 때문에 service 로직이 간결해졌고 repository와 service의 역할을 분리해 줄 수 있었다.  

#### ✏️ 배운점

- 프로젝트를 시작 하기전에 Erd설계를 처음부터 잘 짜 놓은다면 불필요하게 이곳저곳에서 쿼리를 실행 시키지 않아도 된다는 것을 느꼈다.

</div>
</details>

<details>
<summary>Transactional과 변경 감지 기능</summary>
<div markdown="1">

#### 🧐  요구사항

- 메인페이지에 업적 달성률 순으로 상위 4명을 보여주는 ‘베스트탈출러’ api 구현

#### 💣 문제상황

- 코드 수정 후 업적 달성 카운트를 조회해 DB에 업데이트 해주는 메소드가 실행되지 않음

#### 💡시도

1. update 메소드 다음에 JPA save 메소드 추가

2. Entity 조회하는 로직의 위치를 변경

3. DB에 직접 칼럼명을 넣어보고, entity에 null값의 문제인줄알고 primitive type 자료형이 아닌reference type 자료형을 넣어봄

4. 조회 부분이라 `@Transactional` 이 빠져있어서 다시 추가

#### 🙆 의견결정

- 변경감지기능이 잘 작동하지 않았던 것은 transaction readonly true가 적용되어서 update 처리하는 transaction이 제대로 작동하지 않았던 문제였고, 수정 했더니 문제가 해결되었다.

</div>
</details>

<details>
<summary>Https 설정</summary>
<div markdown="1">

#### 🧐 요구사항

- HTTPS는 SSL 또는 TLS라는 암호화 기술을 통해 방문한 웹사이트에 브라우저를 안전하게 연결하여 브라우징 환경을 안전하게 유지한다. 

- 사용자에게 안전한 브라우징 환경을 제공하기 위해 보안이 강화된 Https를 사용하고 싶었다.

### 💣 문제상황

- 무료 SSL 인증서인 Let’s Encrypt와 Certbot을 사용하여 Https 설정을 하려고 했다.
 
- 먼저 80포트로 가상 웹서버를 띄워 인증서를 발급받는 standalone 방식을 적용했는데, 

- apache2가 계속 자동으로 80포트를 실행시켜 오류가 났고,

- 그 이유로 구매해 놓은 도메인이 5번 이상 인증에 실패해 몇시간 동안 인증시도가 불가한 상황에 처했다.

### 💡해결방안

1. Let’s Encrypt + Certbot

   해당 도메인 인증제한이 풀릴때까지 기다리거나 새로운 도메인을 구입해 시도하기

2. AWS Certificate Manager + AWS Route53

   새로운 인증방식 시도하기

#### 🧐 의견결정

- 런칭 기간이 얼마 남지 않았고, 시간이 오래 소요될 수록 유저피드백을 받을 수 있는 기간이 줄어들기 때문에 빠른 해결이 필요해 비교적 간단한 AWS Certificate Manager를 이용한 방법으로 재시도 했다.

</div>
</details>

<details>
<summary>이미지 리사이징을 통한 성능개선</summary>
<div markdown="1">

#### 💣 문제상황

- 업체/테마 조회할 때 속도가 느린것이 느껴졌고, Lighthouse 성능개선 필요 문구확인하였다.

#### 💡해결방안

1. AWS lamda를 이용한 이미지 리사이징

2. jpeg와 png 파일을 WebP형식으로 변환

#### 🪄 개선결과

- WebP형식으로 가지고 있는 700여장의 이미지를 변환했을 때 

- 실제로는 속도가 많이 줄어보였지만, Lighthouse에서는 성능개선이 조금밖에 되지 않았습니다. 

- 추후 다른 방식의 성능개선 방식을 더 찾아볼 계획입니다.

</div>
</details>
  
<details>
<summary>로그인 체크</summary>
<div markdown="1">

#### 🧐 요구사항

- 로그인 시 해당 유저의 정보를 저장하여 유저 정보가 필요한 부분에서 사용하고 또한 로그아웃 버튼과 마이페이지 버튼은 로그인 유무로 판별되기 때문에 로그인이 되어있는지 체크가 필요하다.

#### 💣 문제상황

- 처음 로그인을 할 때, 로그인 체크 전역변수를 만들어서 로그인을 하면 true, 로그아웃을 할 때 false가 되도록 만들었다. 

- 하지만 부득이한 이유로 페이지를 새로고침 하게 되면 state값이 사라져서 실제로 토큰은 들고 있지만 로그인 체크 변수가 false상태가 되는 문제가 있었다.

#### 💡 해결방안

1. 헤더에 로그인 체크 API를 만들어 전역변수로 관리한다.
   : 간편하게 구현되며 직면한 문제도 쉽게 해결될 수 있다고 생각이 들었다. 하지만 방안 2의 경우 굳이 서버와 여러번 통신하지 않아도 문제를 해결할 수 있기 때문에 방안2를 최대한 이용하기로 생각했다.
2. 로그인시 받은 토큰과 유저정보의 유무를 이용하여 관리한다.
   : 새로고침 하여도 휘발되지 않는 session storage에 로그인 시 받은 유저 정보와 토큰을 저장하여  useEffect를 통해 session storage에 있는 유저 정보를 받아오고, 
     유저 정보의 유무에 따라 로그인 체크 전역변수를 한번 더 true나 false로 변경하여 새로고침 하여도 유저 로그인 상태를 구별할 수 있게 되었다.

#### ✏️ 배운점

- SPA을 만들면서 사이트가 새로고침 될 일이 별로 없다고 생각했는데, 실제 웹사이트를 사용 할 유저가 어떻게 사용할지 모르므로 예상되는 다양한 문제점을 미리 많이 고민해봐야 한다는 것을 알게 되었다.

</div>
</details>

<details>
<summary>좋아요 기능의 느린 반응</summary>
<div markdown="1">

#### 🧐 요구사항

- 업체별, 테마별 페이지에 리스트 형태로 있는 각각 업체 or 테마들의 리스트에서 직접 좋아요 기능을 누를 수 있도록 하였다. 
 
- 이는 업체나 테마의 상세페이지에 들어가지 않고 리스트에서 미리 찜해두고 나중에 마이페이지에서 찾아볼 수 있도록 하기 위한 기능이다.

#### 💣 문제상황

- 각 회원이 좋아요를 누른 유무는 업체나 테마별 리스트를 불러올 때 response에 불리언값으로 받게 된다. 

- 따라서 내가 특정 테마의 좋아요를 누르면 나머지 리스트를 refetch하고 변화된 해당 컴포넌트의 좋아요의 색상이 바뀌게 되는 방법이다. 

- 이 경우 리스트를 refetch하는 동안 약간의 딜레이가 체감된다. 

#### 💡 해결방안

- 클릭 시 유저는 refetch를 기다릴 필요 없이 버튼을 누름과 동시에 색상이 바뀌어야 기능이 빠르게 작동한다고 인식할 것이다. 

- 따라서 좋아요 색상을 바꾸는 state를 따로 만들어서 클릭 시 true값이 되도록 useState를 하나 만들고, 
  List를 불러올때도 해당 state값을 서버에서 받은 데이터에 따라 setState해주는 방식으로 서버의 데이터에도 만족을 하면서 속도도 빨라 보이도록 하였다. 

#### ✏️ 배운점

- 기능의 성능 자체를 빠르게 만드는 것이 제일 중요하겠지만, 기능 사용에 지장을 주지 않으면서 유저가 더욱 쾌적하게 사이트를 사용 할 수 있는 방법 또한 있다는 것을 느꼈다.

</div>
</details>



<p align="right">(<a href="#Top">맨 위로</a>)</p>

## 🧑‍🤝‍🧑 팀원 소개

| 정영훈                               | 김휘린                                  | 박혜민                                  | 이기재                                 | 남궁은                                   | 한수진                                  | 전현주     |
| ------------------------------------ | --------------------------------------- | --------------------------------------- | -------------------------------------- | ---------------------------------------- | --------------------------------------- | ---------- |
| FE                                   | FE                                      | FE                                      | BE                                     | BE                                       | BE                                      | UI/UX      |
| ENTP                                 | INTP                                    | ENFJ                                    | ESFP                                   | ENTJ                                     | INFP                                    | ENTP       |
| [:link:](https://github.com/clorose) | [:link:](https://github.com/Hwirin-Kim) | [:link:](https://github.com/hyemin0901) | [:link:](https://github.com/Liam-Geni) | [:link:](https://github.com/ggggraceful) | [:link:](https://github.com/soojin-dev) | [:link:]() |

<p align="right">(<a href="#Top">맨 위로</a>)</p>

## 📝 라이센스

우리 라이센스 있음

<p align="right">(<a href="#Top">맨 위로</a>)</p>

## 🙏 도움주신분들 | Special Thanks

구글 선생님에게 도움을 받았겠지만 특별히 이분에겐 감사합니다 하는 사이트.

<p align="right">(<a href="#Top">맨 위로</a>)</p>
