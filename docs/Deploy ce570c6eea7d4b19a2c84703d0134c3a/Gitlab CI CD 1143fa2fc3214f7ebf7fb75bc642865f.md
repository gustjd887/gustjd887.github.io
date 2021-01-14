# Gitlab CI/CD

gitlab docs 공식문서 번역해서 공부할 것

1. 코드 푸시
2. 코드 테스트(django, python, admin)
    1. django
        1. 웹사이트 접근 가능한지
        2. 데이터베이스 접근 가능한지
    2. python
        1. 파싱 오류 없는지
        2. 데이터베이스 접근 가능한지
    3. admin
        1. admin 페이지 접근 가능한지
        2. 데이터베이스 접근 가능한지
3. 도커 latest 버전 이미지 빌드
4. 코드 테스트 성공 시 쿠버네티스에 최신버전 배포
    1. issuesite
    2. issuecollector
    3. issueadmin