# JS 에서 독특한 데이터 : falsy : 거짓같은 값

- 자체적으로 변수에 값을 저장하지 않거나, 일부 특별한 값을 저장하면 마치 변수가 boolean 처럼 작동하는 것

### 다음은 JavaScript의 거짓 같은 값들입니다.

| 값           | 타입      | 설명                                                                                                                        |
| ------------ | --------- | --------------------------------------------------------------------------------------------------------------------------- |
| null         | Null      | null 키워드는 아무런 값도 없음을 의미합니다.                                                                                |
| undefined    | Undefined | undefined는 원시값을 의미합니다.                                                                                            |
| false        | Boolean   | false 키워드.                                                                                                               |
| NaN          | Number    | NaN은 숫자가 아님을 의미합니다.                                                                                             |
| 0            | Number    | The Number 0, 0.0, 0x0 등도 포함합니다.                                                                                     |
| -0           | Number    | The Number 음수 0, -0.0, -0x0 등도 포함합니다.                                                                              |
| 0n           | BigInt    | The BigInt 0, 0x0n 등도 포함합니다. Note that there is no BigInt에 음수 0가 없다는 것에 주목하세요. 0n의 음수 0은 0n입니다. |
| ""           | String    | 비어있는 string 값, also '' 및 ``도 포함합니다..                                                                            |
| document.all | Object    | JavaScript의 유일한 거짓 같은 객체는 내장 document.all입니다.                                                               |

- `const name = ""` : `name` 변수에 담긴 값이 `falsy` 가 된다

## falsy 를 활용한 코드 예제

```js
if(name === "") {} : name 변수에 저장된 문자열이 비어있을때
if(!name) {} 으로 사용할 수 있다

if(num === 0) {} : num 변수에 저장된 숫자가 0일때
if(!num) {} 으로 사용할 수 있다.

// 아래 코드는
if(name !== null) result = name
else result = "Korea"
// 다음과 같이 사용할수 있다
result = name || "Korea

// nation 변수의 값이 falsy 가 아니면
// result 변수에 "Republic of Korea" 문자열을 저장하라
const nation = "Korea"
const result = nation && "Republic of Korea"


const arr = []
if(arr.length > 1) {
    const result = arr[1]
}
// 위의 코드는 아래처럼 가능
const arr = [1,2,3,4,5,6,7,8]
const result = arr && arr[1]



```
