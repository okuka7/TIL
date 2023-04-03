# document.querySelector();

__querySelector__ 는 name이나 id를 제한하지 않고 CSS 선택자를 사용하여 요소를 찾습니다.  
괄호 한에 들어가는 매개변수는 CSS에서 유효한 선택자여야 합니다.
반환 객체는 한 개의 요소만 할 수 있으며 동일한 객체의 이름을 가진 객체가 있으면 문서 내의 첫 번째 요소를 반환합니다.

```
document.querySelector('h1');
document.querySelector('.name');
ducoment.querySelector('#name');
```
_('h1') : h1태그의 요소중 첫번째 h1을 리턴합니다._  
_('.name') : .name의 class를 반환합니다._  
_('#name') : name의 id를 반환합니다._  

---
### 프로젝트를 하면서 적용했던 부분  
로그인 화면을 구성하던 중에 회원가입 버튼을 누르면 회원가입 창이 나오고 로그인 버튼을 누르면 로그인 창이 나오는 것을 구현하다가 적용하게 되었다.

```
const wrapper = document.querySelector('.wrapper');
const loginLink = document.querySelector('.login-link');
const registerLink = document.querySelector('.register-link');

registerLink.addEventListener('click',()=> {
  wrapper.classList.add('active');
  });
loginLink.addEventListener('click',()=> {
  wrapper.classList.remove('active');
  });
```
