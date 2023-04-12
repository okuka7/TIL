# componant

리액트는 사용자가 볼수있는 여러가지 컴포넌트로 이루어져 있습니다.  
  컴포넌트란 __리액트를 이루고 있는 최소한의 단위__ 입니다.  
  컴포넌트는 함수형, 클래스형 두가지가 있습니다.  
  
  * __함수형 컴포넌트__ function으로 정의하고 return에 jsx를 반환합니다.  
  ```
  function Hello() {
    return (
      <div> 
        hello
      </div>
    )
   }
  ```
  * __클래스형 컴포넌트__  class로 정의하고 render()에서 jsx를 반환합니다.
  
 ```
 class Hello extends Componats {
   render () {
    return (
      <div>
        hello
      </div>
     );
    }
  }
  ```
  
  ### 언제 componant를 사용하면 좋을까?
  1. 반복되는 html 축약할 때
  2. 큰 페이지 만들 때
  3. 자주 변경되는 것들을 작성할 때
   
 
