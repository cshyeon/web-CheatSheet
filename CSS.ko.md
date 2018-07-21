# CSS cheat sheet
Lists are arranged alphabetically.

---

- a 태그 사용시 텍스트 밑줄 제거
```css
text-decoration:none;
```

- pseudo class selector
```css
:link - 방문한 적이 없는 링크
:visited - 방문한 적이 있는 링크
:hover - 마우스를 롤오버 했을 때 
:active - 마우스를 클릭하여 누르고 있을 때
:focus - 해당 엘레먼트가 포커스 상태일 경우
```

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