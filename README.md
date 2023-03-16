
<!-- ### 서버 시작하기



```shell
$ git clone https://github.com/KPUHeyDoctor/docker.git
$ git submodule update --recursive --remote --init
$ cd frontend
$ yarn
$ yarn build
$ cd ..
$ docker-compose up --build -d
``` -->

### 가상서버에서 docker.dev 돌려보기
```shell
$ git clone https://github.com/KPUHeyDoctor/docker.git
$ git submodule update --recursive --remote --init
$ cd frontend
$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
. ~/.nvm/nvm.sh
$ nvm install node
$ npm install --global yarn
$ yarn
$ yarn build
$ cd ..
$ docker-compose -f docker-compose.yml up -d
```
