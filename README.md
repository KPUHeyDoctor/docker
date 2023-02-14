
### 서버 시작하기



```shell
$ git clone https://github.com/KPUHeyDoctor/docker.git
$ git submodule update --recursive --remote --init
$ cd frontend
$ yarn
$ yarn build
$ cd ..
$ docker-compose up --build -d
```

### 개발 서버 시작하기

```shell
$ git clone https://github.com/KPUHeyDoctor/docker.git
$ git submodule update --recursive --remote --init
$ docker-compose -f docker-compose-dev.yml up -d
```