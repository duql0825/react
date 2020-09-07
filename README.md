<h1> 개요 </h1>  

> react todolist  
> material-ui  

<h2> How to run </h2>

### Installation  

### react-icons
간단한 아이콘들을 import 해서 사용할 수 있다.  
```
npm install react-icons --save  

ex)  
import { MdAdd } from "react-icons/md";  
<MdAdd />
```

### styled-components
```
$ npm i styled-components

import styled from "styled-components"

ex) 
const Text = styled.div`
  flex: 1;
  font-size: 21px;
  color: #495057;
  ${props =>
    props.done &&
    css`
      color: #ced4da;
    `}
 
 <Text done={done}>{text}</Text>
```

## Getting started
```  
npm i 
npm run start
```  

# 설명

-------------------------------------------------------
## 구성요소
-------------------------------------------------------


### components : todo  
> memo를 사용해 렌더링 속도 증가  
> styled component를 사용해서 css-in-js 사용  
> react-icon 에서 간단한 아이콘 불러오기  


## 참고 자료
fast campus 강의
