# state

State는 컴포넌트 내에서 지속적으로 변경이 일어나는 값을 관리하기 위해 사용합니다.  
자동으로 html에 반영되게 만들고 싶을 때 사용합니다.  
__자주 변경될거 같은 html부분은 state로 만들어 놓으면 좋습니다.__

```
import { useState } from 'react';

let [countA, countB] = useState('clickNumber');
```
## 연습하기

```
import { useState } from 'react';

  let [ 제목 , a ] = useState('일기');
  
    <div>
      <h4>{ 제목 } </h4>
    </div>
