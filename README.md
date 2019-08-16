# Movie app 2019

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
