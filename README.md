# 0623Start

## :clipboard: 목차

- :books: <a href="#outline">개요</a>
- :wrench: <a href="#tech">기술 스택</a>
- :scroll: <a href="#erd">ERD(Entity-Relation Diagram)</a>
- :family: <a href="#team">팀원 역할 소개</a>
- :bookmark_tabs: <a href="#function">기능</a>
- :mag_right: <a href="#fullfill">보완할점</a>

# :books: <a name="outline">개요</a>
<br>

> **프로젝트** : DB 활용 자유 주제 - 모의 경매 프로그램
>
> **프로젝트 이름** : Now Auction
>
> **분류** : 팀 프로젝트
>
> **제작 기간** : 2023.06.23 ~ 2023.07.05
>
> **주제 선정 이유** : 경매와 같이 실시간으로 시간과 가격이 변동되는 프로그램을 구현하고 싶어서
> 
> **주 사용자층** : 경매를 하고 싶지만 경매에 대해 익숙하지 않은 사람
>
> **프로젝트 목표** :
> 1. 사용자에게 경매에 대한 경험 제공
> 2. 실시간 DB 상호작용
> 3. 실제 경매사이트랑 유사하게 만들어보기

<br>

# :wrench: <a name="tech">기술 스택</a>

<h4>데이터베이스</h4>
<div align="left">
   <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</div> 
<h4>언어</h4>
<div align="left">
    <img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=Java&logoColor=white"/>
</div>

<h4>API</h4>

[![MyGet pre-release](https://img.shields.io/myget/quartznet/vpre/Quartz)](#)

<h4>협업도구</h4>
<div align="left">
   <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white" />
   <img src="https://img.shields.io/badge/FIGMA-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
</div>

# :scroll: <a name="erd">ERD</a>

## 초기 ERD
<img src="https://github.com/Psh230412/0623Start/assets/110301333/18db84d4-60bd-4e4a-bef4-4cfb32e1143a" width="100%"/>

## 현재 ERD
<img src="https://github.com/Psh230412/0623Start/assets/110301333/3490b2b3-f836-43f1-a86f-0598953c6e90" width="100%"/>

### 변경이유
1. 낙찰/유찰된 물품을 포함한 전체 물품을 관리하는 copy_auction과 </br>
   경매 진행 중인 물품을 관리하는 auction으로 구분 하여 목적에 맞게 테이블 활용이 용이하도록 함
2. 낙찰/유찰 여부를 한 테이블로 관리함


# :family: <a name="team">팀원 역할 소개</a>
<br>

| 이름 | 박상현 - 팀장 | 김명완 | 김민아 | 성지수 | 이정빈
| :---: | :----------: | :----------: | :----------: | :----------: | :----------: |
| 역할 | 기획 </br> 업무 현황 파악 </br> 상품등록 </br> 회원정보변경 | DB관리 </br> 물품검색 </br> 캐시구현 | 디자인 총괄 </br> 사용설명서 | 회원가입 </br> 로그인 </br> 디버깅 </br> 메인 분류 | 스케줄러 </br> 마이페이지 </br> 메인 정렬 </br> 입찰화면 |

# :scroll: <a name="function">기능</a>
[상세보기](https://github.com/JeongBin0462/Now-Auction/blob/master/Presentation.md)

# :mag_right: <a name="#fullfill">보완할점</a>
### 1. 금액 충전, 결제시스템 추가
### 2. 입찰한 물품에 상위입찰이 들어오면 기존 입찰자에게 정보제공
### 3. 낙찰/유찰된 내역 삭제, 유찰물품 재등록
### 4. 이미 등록한 물품에 대한 정보 수정 기능
