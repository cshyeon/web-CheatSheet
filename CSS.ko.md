# CSS cheat sheet
Lists are arranged alphabetically.

---

- a 태그 사용시 텍스트 밑줄 제거
```css
text-decoration:none;
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