# Movie app 2019
### https://alexsando86.github.io/movie_app_2019/

React JS Fundamentals Course (2019 update!)

### PropTypes
* 타입을 체크해서 실수를 줄여준다.
* isRequired를 사용하게 되면 필수타입이 존재해야함., 사용하지 않으면 타입이 없어도 에러가 나지 않는다.
``` 
npm install prop-types 
```
``` 
Food.propTypes = {
  name: PropTypes.string.isRequired,
  rating: PropTypes.number.isRequired,
  picture: PropTypes.string.isRequired
};
```

* setState를 호춣 할때마다 리액트는 새로운 state와 render function을 호출 한다.

### componentDidMount
* render 수행 후 호출되는 함수.
```
componentDidMount() {
    console.log("DidMount")
}
```
### componentDidUpdate
* 컴포넌트가 업데이트 될때 마다 호출되는 함수
```
componentDidUpdate() {
    console.log("DidUpdate")
}
```

* jsx에서는 리액트의 class와 겹치기 때문에 className을 사용한다.

### gh pages
```
npm i  gh-pages
```


* gh-page설치 npm install gh-pages
* package.json에 homepage를 선언한다.
  - https:{your github username}.github.io/{the name of your project in github}
  - githubID.github.io/저장소이름
  - alexsando86.github.io/movie_app_2019
* deploy, predeploy를 만든다.
  - deploy는 build폴더를 upload한다.
  - deploy를 실행하면 predeploy가 자동으로 실행된다.
  - 

  Github jenkins test