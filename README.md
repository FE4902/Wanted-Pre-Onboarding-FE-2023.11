## 사전과제
### Q1. 내가 생각하는 클린 코드란?
정해진 규칙에 맞춰서 작성되어있으며, 코드를 작성하지 않은 사람이 보더라도 보기 좋은 코드가 클린 코드라고 생각합니다.

### Q2. 내가 생각하는 (프론트엔드에서의) 클린 코드란?
1번의 답변처럼 생각하고 있습니다.

### Q3. 내가 클린코드보다 중요하게 생각하는 것은?
마감 기한과 에러 없이 정상적으로 작동하는 코드, 외주 업체에서 일을 했었어서 기한 내에 오류없이 작동하는 것이 제일 우선이 되었습니다.

### Q4. 다음 중 선호하는 방식과 그 이유는?
#### 1. Tab vs Space 
Tab, 한 번만 쳐서 들여쓰기가 되는게 편리해서 Tab을 사용하고 있습니다.

#### 2. 세미콜론 O vs 세미콜론 X 
세미콜론 O, 세미클론을 사용하는 것이 코드의 마지막을 명확하게 알 수 있어서, 자동으로 세미콜론이 붙도록 Prettier를 설정해서 사용하고 있습니다.

#### 3. count++; vs count += 1; vs count = count + 1;
`count++` 와 `count += 1` 혼용, 1씩 증가할때는 `++`, 다른 수 다른 수식을 이용할때는 `+=` 이렇게 사용하는게 간결해서, 두 가지를 혼용해서 사용하고 있습니다.

####  4. if (isLogin) {} vs if (isLogin === true) {} 
`if (isLogin) {}`, `isLogin` 자체가 `boolean` 이므로 `true`와 비교하지 않고, `if (isLogin) {}` 를 사용하고 있습니다.

#### 5. isLogin && <HelloWanted /> vs isLogin ? <HelloWanted /> : <></> vs isLogin ? <HelloWanted /> : null vs isLogin ? <HelloWanted /> : undfined 
`isLogin && <HelloWanted />`, 다른 코드보다 간결해서 `isLogin && <HelloWanted />` 를 사용하고 있습니다.
