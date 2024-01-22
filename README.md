# 개요
간단한 커머스 쇼핑몰 프로젝트

skill : Spring, Jpa, Mysql, Redis, Docker, AWS

목표 : 셀러와 구매자 사이를 중개해 주는 커머스 서버를 구축한다. 

## 회원
### 공통
- [ ] 이메일을 통한 인증번호 확인으로 회원가입

## 고객
- [ ] 회원 가입
- [ ] 인증 처리 (EMAIL)
- [ ] 로그인 토큰 발행
- [ ] 로그인 토큰을 통한 제어 확인 ( JWT와 Filter를 이용해 간략하게 )
- [ ] 예치금 관리

### 셀러
- [ ] 회원 가입

## 주문
### 셀러
- [ ] 상품 등록, 수정
- [ ] 상품 삭제

### 고객
- [ ] 장바구니를 위한 Redis 연동
- [ ] 상품 검색 & 상세 페이지
- [ ] 장바구니에 물건 추가
- [ ] 장바구니 확인
- [ ] 주문하기
- [ ] 주문내역 이메일로 발송하기
