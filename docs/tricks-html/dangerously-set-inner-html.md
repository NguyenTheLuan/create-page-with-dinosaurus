---
sidebar_position: 1
---

## 1.Example type code:

### 1.1 Shit code example:

![string](./../../static/img/tutorial/dangerously-set-inner-html/Untitled.png)

### 1.2 Golden code example:

![alt](./../../static/img/tutorial/dangerously-set-inner-html/Untitled1.png)

## 2.How to fix:

```jsx title="src/pages/my-react-page.js
const bien = `test <b> bold </b>`;
<div dangerouslySetInnerHTML={{ __html: bien }}></div>;
```

### 3.Example code:

![alt](./../../static/img/tutorial/dangerously-set-inner-html/code.png)
