# NVM (Node Version Manager)

로컬 환경에서 다양한 버전의 Node.js 를 관리 할 수 있음 (설치, 버전 스위칭)

## Install

!!! note    

    Windows 환경에서 Nvm 설치를 진행

릴리즈된 최신버전의 nvm-install.exe 를 다운로드 받아 설치

```
https://github.com/coreybutler/nvm-windows/releases
```

## Command
자주 쓰는 명령어만 정리

### install
``` console title="node 특정 버전 설치"
nvm install 8.9.2
```
``` console title="node 최신 버전 설치"
nvm install latest
```
``` console title="node 최신 버전 (LTS) 설치"
nvm install lts
```

### list
``` console title="로컬에 설치된 node 리스트"
nvm ls
```

### use
``` console title="특정 버전 node 사용"
nvm use 8.9.2
```
``` console title="lts 버전 node 사용"
nvm use lts
```
``` console title="최신 버전 node 사용"
nvm use latest
```
``` console title="가장 최근에 설치된 node 사용"
nvm use newest
```

### current
``` console title="현재 사용중인 node 버전 표시"
nvm current
```

### uninstall
``` console title="특정 버전 node 제거"
nvm uninstall 8.9.2
```
``` console title="lts 버전 node 제거"
nvm uninstall lts
```
``` console title="최신 버전 node 제거"
nvm uninstall latest
```
