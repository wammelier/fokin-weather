# Fokin Weather


1. Bridge 란?
IOS 나 Android 의 코어 즉 네이트브와 JavaScript를 연결하기위한 다리이다. 간단한 인스타그램같은 어플들은 사진이나 코멘트 같은 데이터를 가져오는것은 간단하게 가져올수 있지만 3D같은 고용량 데이터를 처리하는데 있어선 굉장히 느릴수 있다.
2. <Text></Text> ??
리엑트네이티브에선 글자는 무조건 text 태그 안에 들어가야한다. 그 이유는 자바스크립트는 브릿지를 이용하기 때문이다.
3. StyleSheet API ?
리액트네이티브에선 일반적인 css사용이 불가능하다. 따라서 css를 오브젝트처럼 만들어서 사용해야만 한다. 
4. flex?
container를 뜻함. 만약 container하위에 많은 flex container가 존재한다면?
그렇다면 숫자가 클수록 화면을 차지하는 비율이 커진다.

```jsx
const styles = StyleSheet.create({
	container: {
		flex: 1,
		backgroundColor: "#fff",
		alignItems: "center",
		justifyContent: "center"
	} 
```

- flexdirection default
flexdirection 의 디폴트는 column이다. 웹사이트의 경우는 row 임

```jsx
const styles = StyleSheet.create({
	container: {
		flexdirection: column
	} 
```

- <view>
리액트네이티브의 view태그는 html 의 div와 같다.

```jsx
const style = StyleSheet.create({
	container: {
		flex:1 ,
		alignItems: "center",
		justifyContent: "center"
	},
	yellowView: {
		flex: 1,
		backgraoundColor: "yellow"
	},
	blueView: {
		flex:1,
		bakcgroundColor: "blue"

```
