# instacart-market-springboot
Kaggle의 Instacart Market Basket Analysis 을 이용한 대용량 데이터 적재 및 Cache Server 구현

## Context

### ACs - Biz

- 사용자는 가장 최근에 구매한 상품을 20 ~ 100개까지 볼  수 있습니다.
- 사용자는 가장 많이 구매한 상품을  20 ~ 100개까지 볼 수  있습니다.
- 사용자는 카테고리별로 상품을 20 ~ 100개까지 볼  수 있습니다.
- 사용자는 상품을  검색할  수 있습니다.

### ACs - Tech

- 상품 구매 기록을 한 대의 서버(지금 현재 사용하고 있는 노트북)에서 빠르게 적재합니다.
  - 상품 관련 캐시 서버의 구현을 통해 각종 검색 및 조회 기능을 최적화 합니다.
  - 대용량 데이터의 적재를 배치와 stream 으로 각각 구현합니다.
- 회원의 인증/인가는 구현하지 않습니다.
- 회원은 구현하지 않습니다.

## Challenge

### 대용량 데이터를 서버를 늘리지 않고 어떻게 효율적으로 적재할 것인가?
- kafka stream vs batch vs grpc 비교하기


### 대용량 데이터에서의 캐시 서버를 어떻게 구현할 것인가? 

### 한 순간에 몰리는 고객의 구매 기록을 어떻게 처리해 볼 것인가? 

<br>
<br>

## Overall Architecture

<br>
<br>

## APIs & Data Model
<br>

### Data Model
<br>


-
