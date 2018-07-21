# CSS cheat sheet
Lists are arranged alphabetically.

---

## 자주찾는 CSS

- [class 선택자](#class-selector)
- [id 선택자](#id-selector)
- [tag 선택자](#tag-selector)
- [descendant 자손 선택자](#descendant-selector)
- [복수 선택자](#multiple-selector)

## index
| 알파벳 | 한글 자음|
|--------------|----|
| [a](#a-index) | [ㄱ](#kr-ga-index)
| [b](#b-index) | [ㄴ](#kr-na-index)
| [c](#c-index) | [ㄷ](#kr-da-index)
| [d](#d-index) | [ㄹ](#kr-ra-index)
| [e](#e-index) | [ㅁ](#kr-ma-index)
| [f](#f-index) | [ㅂ](#kr-ba-index)
| [g](#g-index) | [ㅅ](#kr-sa-index)
| [h](#h-index) | [ㅇ](#kr-a-index)
| [i](#i-index) | [ㅈ](#kr-ja-index)
| [j](#j-index) | [ㅊ](#kr-cha-index)
| [k](#k-index) | [ㅋ](#kr-ka-index)
| [l](#l-index) | [ㅌ](#kr-ta-index)
| [m](#m-index) | [ㅍ](#kr-pa-index)
| [n](#n-index) | [ㅎ](#kr-ha-index)
| [o](#o-index) |
| [p](#p-index) |
| [q](#q-index) |
| [r](#r-index) |
| [s](#s-index) |
| [t](#t-index) |
| [u](#u-index) |
| [v](#v-index) |
| [w](#w-index) |
| [x](#x-index) |
| [y](#y-index) |
| [z](#z-index) |

### <a id="a-index"></a>a
- a 태그 사용시 텍스트 밑줄 제거
```css
text-decoration:none;
```  
### <a id="b-index"></a>b

### <a id="c-index"></a>c
- <a id="class-selector"></a>class 선택자
```html
<div class="div-class"></div>
<style>
    /* 클래스명이 'div-class'인 모든 엘리먼트 */
    .div-class { }
</style>
```

### <a id="d-index"></a>d
- <a id="descendant-selector"></a>descendant(자손) 선택자
```html
<div id="div-id">
    <a href="#">선택 됨</a>
    <ul>
        <li> <a href="#">이것도 선택 됨</a> </li>
    <ul>
</div>
<style>
    /* div 내의 모든 a tag들이 선택됨 */
    div a { color: red; }
</style>
```
### <a id="e-index"></a>e
### <a id="f-index"></a>f
### <a id="g-index"></a>g
### <a id="h-index"></a>h

### <a id="i-index"></a>i
- <a id="id-selector"></a>id 선택자
```html
<div id="div-id"></div>
<style>
    #div-id { }
</style>
```

### <a id="j-index"></a>j
### <a id="k-index"></a>k
### <a id="l-index"></a>l
### <a id="m-index"></a>m
### <a id="n-index"></a>n
### <a id="o-index"></a>o

### <a id="p-index"></a>p
- pseudo class selector
```css
:link - 방문한 적이 없는 링크
:visited - 방문한 적이 있는 링크
:hover - 마우스를 롤오버 했을 때 
:active - 마우스를 클릭하여 누르고 있을 때
:focus - 해당 엘레먼트가 포커스 상태일 경우
```
### <a id="q-index"></a>q
### <a id="r-index"></a>r
### <a id="s-index"></a>s
### <a id="t-index"></a>t
- <a id="tag-selector"></a>tag 선택자
```html
<div id="mydiv"></div>
<style>
    /* 모든 div tag에 Css 적용 */
    div { text-align: center; }
</style>
```

### <a id="u-index"></a>u
### <a id="v-index"></a>v
### <a id="w-index"></a>w
### <a id="x-index"></a>x
### <a id="y-index"></a>y
### <a id="z-index"></a>z
------------------------------------------------------

### <a id="kr-ga-index"></a>ㄱ
### <a id="kr-na-index"></a>ㄴ
### <a id="kr-da-index"></a>ㄷ
### <a id="kr-ra-index"></a>ㄹ
### <a id="kr-ma-index"></a>ㅁ
### <a id="kr-ba-index"></a>ㅂ
- 반응형 웹 설정
```css
.container {
    display: flex;
    flex-flow: row wrap;
    text-align: center;
    align-items: center;
    justify-content: center;
}

.child {
    display: inline-flex;
    width:30%;
    min-width:400px;
}

img { max-width: 100%; }
```

- <a id="multiple-selector"></a>복수(다중) 선택자
```html
<div id="mydiv"></div>
<span class="myspan"></span>
<style>
    /* 모든 div와 추가로 모든 myspan클래스 엘레먼트가 선택됨*/
    div, .myspan { text-align: center; }
</style>
```


### <a id="kr-sa-index"></a>ㅅ
### <a id="kr-a-index"></a>ㅇ
### <a id="kr-ja-index"></a>ㅈ
### <a id="kr-cha-index"></a>ㅊ
### <a id="kr-ka-index"></a>ㅋ
### <a id="kr-ta-index"></a>ㅌ
### <a id="kr-pa-index"></a>ㅍ
### <a id="kr-ha-index"></a>ㅎ

