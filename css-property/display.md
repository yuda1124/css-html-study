display: 대상 엘리먼트에 사용되는 렌더링 박스의 유형을 결정해주는 css 속성
display property는 키워드 값을 사용하여 지정되며 키워드 값은 6 가지 카테고리로 분류된다.

1. display-outside
엘리먼트에 의해 생성 된 박스의 외부 디스플레이 타입을 지정하여 엘리먼트가 어떻게 부모 포맷팅 컨텍스트에 참여 하는지를 지시한다.
block: 이 Element는 block element box를 만든다.
inline: 이 Element는 하나 혹은 이상의 inline element box를 만든다.

2. display-inside
엘리먼트에 의해 생성 된 박스의 내부 디스플레이 타입을 지정하며, 그 내용이 박스 안에 어떻게 배치되는지 지시한다.
table: 이 Element는 <table> HTML Element처럼 동작합니다. block-level box를 정의합니다.
block-level box vs block element box의 차이를 알아볼 것

flex: 이 Element는 block element 처럼 동작하고 flexbox 모델에 따라 내용을 배치합니다.
grid: 이 Element는 block element 처럼 동작하고 grid 모델에 따라 내용을 배치합니다.
grid랑 flexbox에 대해 알아볼 것

3. display-listitem
이 Element는 내용을 위한 block box와 개별 list-item의 inline box를 만듭니다.
명시된 display inside 값이 없으면 box의 inner display-type은 flow가 됩니다.
명시된 display outside 값이 없으면 box의 outer display-type은 block이 됩니다.

4. display-internal
이 섹션에서는 특정 레이아웃 모드 내에서만 의미있는 "내부" display 값을 정의합니다.
table-row-group: <tbody> HTML Element 처럼 동작한다.
table-header-group: <thead> HTML Element 처럼 동작한다.
table-footer-group: <tfoot> HTML Element 처럼 동작한다.
table-row: <tr> HTML Element 처럼 동작한다.
table-cell: <td> HTML Element 처럼 동작한다.
table-column-group: <colgroup> HTML Element처럼 동작한다.
table-column: <col> HTML Element처럼 동작한다.
table-caption: <caption> HTML Element처럼 동작한다.

5. display-box
이 값은 요소가 display box를 생성하는지 여부를 정의합니다.
none: 레이아웃에 영향을 미치지 않도록 요소의 표시를 끈다.
