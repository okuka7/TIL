# if

if문은 지정한 조건이 참인 경우 명령문을 실행합니다.  
조건이 __거짓__ 인 경우 또 다른 명령문이 실행될수 있습니다.

```
if(조건1) {
  명령문1
  } 
else if {
  명령문2(조건2) 
  }
else {
  명령문3 
  }
  ```
  
  ## 적용했던 부분
  ```
  window.addEventListener('click',function(e){
      if(btnPopup.contains(e.target)){
        wrapper.classList.add('active-popup')
      }
      else if(wrapper.contains(e.target)){
      }
      else{
        wrapper.classList.remove('active-popup');
      }
  });
 ```
 메뉴창 외부 영역을 클릭 시 팝업이 꺼지는 기능을 만들고 싶었다. 그래서 if 문을 쓰기로 했다.  
 버튼을 누르면 wrapper에 active-popup이 추가 되고, wrapper를 눌러도 active-popup이 추가된다.  
 그 외 창을 누르면 active-popup을 remove 한다.
