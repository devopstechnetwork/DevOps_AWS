# RDS



### 기타

- 다중 AZ 배포
    - 다른 가용 영역(머신)에 대기 RDS에 동기식 복제
    - 고가용성 지원
    - 자동 장애 조치 수행
    - 프리 티어에선 사용할 수 없는 옵션(과금)
    
    
- 퍼블릭 액세스 가능성 : 외부에서 접근할 필요성이 있을 때 
    - 대안 : 테스트 RDS를 만들고 백업파일을 만들고 해당 백업파일로 하는 것이 좋음

- 데이터베이스옵션
    - 데이터베이스이름 : 시작과 동시에 만들어지는 데이터베이스의 이름 
    
    
- AMI : 각 계정 별로 권한을 설정할 때 필요

- 암호화 : 과금후 사용가능

- 백업(*)
    - 7일 백업할 경우, 7일 전까지만 갈 수 있음
    - 유지관리 기관과 백업 기간과 방지하기 위해 설정
    
- 유지관리 기간 : 백업기간과 같으면 안됨
    - 마어니 버전 자동 업그레이드 사용 안함으로 체크 
- 모니터링 : 모니터링 

- 로그 내보내기 : 
    - 느린 쿼리 로그 : 오래걸리는 쿼리를 모니터링 
    

    