# pjtBasement

PJT Basement: 
 - 새 프로젝트를 시작 할 때 빠른 시작을 위한 Base 구조 작업
 - webpack 환경을 구성
 - webpack-dev-server 환경 구성
 - Atomic 폴더구조로 기본 구조 구현
 - start script를 통해서 hot-loading 적용(예정)
 - build script를 구성하여 /public 폴더에 빌드한 html, js, css를 export(예정)

1. [개발 환경](#dev-spec)
2. [설치 및 실행 방법](#installation)
3. [Dependencies](#dependencies)

<h2 id="dev-spec">
    개발환경
</h2>
  - NPM 6.14.5
  - node 12.18.1

<h2 id="installation">
    설치 및 실행 방법
</h2>
  - 프로젝트 루트 디렉토리로 이동합니다.
  cd <다운로드위치>/pjtBasement

  - yarn 종속성을 설치해 줍니다.
  yarn install

  - npm 종속성을 설치해 줍니다.
  npm i

  - webpack-dev-server가 localhost:8080로 자동으로 실행됩니다.
  - <주의> 이미 8000번 포트를 사용하고 있다면 충돌이 날 수 있습니다.
  npm start

<h2 id="dependencies">
    Dependencies
</h2>

@babel/cli: 7.7.0

@babel/core: 7.7.2

@babel/plugin-proposal-class-properties: 7.7.4

@babel/preset-env: 7.7.1

babel-loader: 8.0.6

webpack: 4.41.2

webpack-cli: 3.3.10

webpack-dev-server: 3.9.0
