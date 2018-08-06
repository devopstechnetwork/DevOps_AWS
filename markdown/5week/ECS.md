# ECS (Container orchestrations)

- 클러스터링 
    - 여러 개의 서버를 하나의 서버처럼 사용. 클러스터에 새로운 서버를 추가할 수도 있고 제거 가능. 작게는 몇 개 안 되는 서버부터 많게는 수천 대의 서버를 하나의 클러스터로 만들 수 있음
    - AWS ECS는 AWS EC2 기반으로 클러스터링을 위한 서버로 구축되며 Auto Scaling Group을 통해 자동 확장, 제거 가능
    
- 스케쥴링 : 컨테이너를 적당한 서버에 배포해 주는 작업. 여러대의 서버 중 가장 할일 없는 서버에 배포하거나 그냥 차례대로 배포 또는 랜덤하게 배포하는 전략으로 실행가능
- 서비스 디스커버리 
    - 클러스터 환경에서 컨테이너느 ㄴ 어느 서버에 생설 될지 알 수 없고 다른 서버로 이동할 수 있음
    - 여러 서비스로 배포된 컨테이너를 key/value 형태로 서비스를 찾아주는 기능
    - 같은 기능의 서비스(컨테이너)가 같은 포트를 사용한다 해도 논리적 그룹을 찾아내어 요청 전달 가능

## AWS ALB(Application Load Balancer)

- 사진()