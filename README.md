Base Repository: https://github.com/fcwu/docker-ubuntu-vnc-desktop

## VNC docker image template

git clone후 해당 디렉토리에서 다음과 같이 빌드하면 된다.
```
docker build . --build-arg BASE_IMAGE={원하는 이미지}

# example
docker build . --build-arg BASE_IMAGE=ubuntu
```

vnc 실행 명령어
```
/startup.sh
```
