# 김태형 Babo

## 원본 사이트와 다른 점

### 1. `<div class="headWrap fans">` &rightarrow; `<header>`로 변경. 
<p>내부에 요소 없음</p>

### 2. `<div id="body">` &rightarrow; `<main>`으로 변경. 
<p><code>&lt;body&gt;</code>가 있어 좋아 보이지 않았기 때문</p>

### 3. Nested CSS 적용
<p>비교적 최근에 도입된 CSS 기술이며, <mark>CSS 선택자들을 중첩구조로 작성할 수 있는 기능을 의미한다.</mark> 기존 선택자 방식은 아래 자식 선택자를 선택하기 위해 단순 나열하는 구조로 작성해왔다.</p>
<p>지금까지는 CSS 전처리기인 <b>SASS(SCSS), Less</b> 등을 사용해야만 CSS Nesting을 사용할 수 있었다. 하지만, CSS 자체에 해당 기능이 내장이 되었고 그렇기에 보다 더 선택자 간의 계층 관계를 명확하게 표현할 수 있게 되었다.</p>