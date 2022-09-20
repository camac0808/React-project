# 🎮 React Project - Video Game Searching Page
> 78만여가지의 게임을 검색해보세요!

RAWG gaming api를 사용하여 제작하였습니다.<br>
모든 게임을 검색하고 상세 정보를 확인할 수 있습니다.<br><br>
### 보러가기: <https://camac0808.github.io/React-project>

![메인페이지](mainpage.PNG)


## 프로젝트에 사용된 언어 및 라이브러리

* React 
* Bootstrap
* AOS
* Font-Awesome
* RAWG gaming api

## 프로젝트의 기능 설명

### 1. api fetch loading시 간단한 이모티콘 애니메이션을 추가
![로딩](loading.gif)

### 2. header search 기능 및 hover transition 추가
![헤더](searchbar.gif)

### 3. hamburger button을 눌러서 sidebar 나오는 transition 구현
![사이드바](sidebar.gif)

### 4. login button에 간단한 hover transition과 blur 넣어서 빛나는듯한 효과 구현
![로그인버튼](login-blur.gif)

### 5. boot-strap을 이용하여 login-page 간단하게 구현 (로그인은 되지 않습니다)
![로그인페이지](loginpage.PNG)

### 6. 첫페이지 랜딩시 AOS 라이브러리를 사용하여 game-card 및 title에 fade 효과 구현
![랜딩페이지](aos.gif)

### 7. game-card에 마우스 hover시 상세페이지로 연결되는 link와 간단한 상세정보 하단에 나오도록 구현
![상세페이지](detailpage.gif)

### 8. 하단에 pagination 구현
![페이지네이션](pagination.PNG)

## 배포
```sh
npm i gh-pages
npm run build
npm run deploy
```

## 향후 업데이트 예정
시간이 너무 지체되서 취업하면서 계속 수정할 예정입니다!

* 반응형 구현
* node.js 활용하여 cache이용. 페이지 뒤로가기 앞으로가기
* 상세페이지 css 꾸미기
* 로그인 기능 구현 (firebase)

## 정보

💌메일 – zqzwzazs@gmail.com - gomgom_@naver.com


## 기여 방법

1. (<https://github.com/camac0808/React-project/fork>)을 포크합니다.
2. (`git checkout -b feature/fooBar`) 명령어로 새 브랜치를 만드세요.
3. (`git commit -am 'Add some fooBar'`) 명령어로 커밋하세요.
4. (`git push origin feature/fooBar`) 명령어로 브랜치에 푸시하세요. 
5. 풀리퀘스트를 보내주세요.

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
