# Docker Compose

멀티 컨테이너 구성 정보를 한곳에서 관리하여 하나의 어플리케이션 처럼 구동 및 관리

!!! note "docker compose repo"
    https://github.com/docker/compose/releases


## Install

``` console title="1. 설치 스크립트 다운로드 실행"
sudo curl -L "https://github.com/docker/compose/releases/download/v2.7.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```
!!! tip
    최신버전은 공식 repo 내 releases에서 확인하고 위 url에 버전만 변경해서 설치 가능

``` console title="2. docker compose 권한 설정"
sudo chmod +x /usr/local/bin/docker-compose
```

``` console title="3. symbolic link 설정"
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
```

``` console title="4. docker compose 버전 확인"
docker-compose --version
```