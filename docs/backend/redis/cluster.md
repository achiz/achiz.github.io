# Redis Cluster Congifuration

실제 환경에서 클러스터 구성을 진행하였지만 의도한 테스트와 결과가 상이함으로 점검 목적으로 클러스터 구성을 기록함

!!! note 

    프로덕션 환경에서는 레디스를 failover에 대응하거나 추후 scale-out 등 확장성을 고려하기 위한 목적으로 Cluster로 구성한다.


* redis.conf 설정
* master1-slave1-slave2 구성 ( redis conf 복제 )
* redis_700~ 설정
* redis 클러스터 명령어
* 