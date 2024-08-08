# express-21c

- express-generator through the 21st century: 21세기를 통과하는 express-generator  
  
## NodeJS, Express, Pug, ES6+ module Template

- Enable ES6+ syntax : ES6+ 문법을 사용할 수 있도록 설정  
- Set default view to pug : 기본 view를 pug로 설정  
- Change the template source code to conform to ES6+ grammar: ES6+ 문법에 맞도록 Template 소스 코드 변경  

## 설치(install) : global install

`npm install -g express-21c`

### express project create : express 프로젝트 생성하기  

`express my_project && cd my_project`

### express project create without express-21c install : express-21c 설치 없이 프로젝트 생성하기

`npm uninstall -g express-21c`
`npx express-21c my_project --view=pug && cd my_project`

### 추가 수정사항 : PS

- Add the following code to your app.js file: app.js 파일에 다음 코드 추가  
  

  // Disable the fingerprinting of this web technology. 경고 방지(avoid warning)  
   `app.disable("x-powered-by");`

## :carousel_horse: History

### Since : 2020-12-10

### V21.1.1( 2022. 11. 04 )

- Source Code refactoring

### V21.2.0( 2022. 11. 11 )

- MySQL and Sequelize init sample
- `express project --pug --sequelize`

### V21.2.1( 2022. 11. 26 )

- Mac and Linux Bug Patch

### V21.2.30( 2024. 01. 19)

- Dependency Upgrade

### V21.2.31( 2024. 01. 19)

- `npx 설치 방법 추가`

#### 참조 출처 : Reference source

- <https://github.com/expressjs/generator>
