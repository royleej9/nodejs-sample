# Test

## 관련 모듈

### Jest

- <https://jestjs.io/>
- 테스트 프레임워크

### jest-extended

- <https://github.com/jest-community/jest-extended>
- 별도 설정 필요 API 설정 부분 참고

``` js
// jest.config.js
module.exports = {
  ...
  setupFilesAfterEnv: ['jest-extended']
  ...
}
```

### SuperTest

- <https://www.npmjs.com/package/supertest>
- HTTP 메소드(GET/POST/PUT... 등) 요청 관련 테스트

## 설치

``` bash
npm install --save-dev jest jest-extended supertest
```

## 환경 설정

- jest.config.js

<https://www.albertgao.xyz/2017/05/24/how-to-test-expressjs-with-jest-and-supertest/>
