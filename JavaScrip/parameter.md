# parameter

매개 변수란 함수의 정의에서 전달받은 인수를 함수 내부로 전달하기 위해 사용하는 변수를 의미합니다.
인수란 함수가 호출될 때 함수로 값을 전달해주는 값을 말합니다.
```
function addNum(a, b){ // 매개변수 a,b라는 2개의 매개변수를 가지는 함수 addNum();을 정의함  
  return a + b;
  }

addNum(1,2); // 인수로 1,2를 전달하여 함수를 호출함 6
```

## 연습

버튼을 누르면 div박스가 나오고 닫기 버튼을 누르면 닫기가 되도록 만들었다.  
```<button onclick="openId('아이디')"> ```처럼 parameter를 활용해서 innerHTML로 인수로 전달받아 각 버튼을 누를때마다 아이디와 비밀번호라는 텍스트가 나오도록 만들었다.
```
function clickBtin(clo) {
   document.getElementById('alert').style.display = clo;
}
function openId(id) {
   document.getElementById('title').inner.HTML = id;
   dicoment.getElementById('alert').style.display = 'block'
}
function closeId(pas) {
   document.getElementById('title').innerHTML = pas;
   dicoment.getElementById('alert').style.display = 'block'
}
```
