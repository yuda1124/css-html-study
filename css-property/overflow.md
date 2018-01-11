overflow
해당 엘리먼트의 블록 레벨 컨테이너(block-level container)보다 내용(content)이 너무 클 때
내용을 잘라낼 지, 스크롤 바를 보여줄 지, 혹은 범위를 넘어가게 보여줄 지를 기술한다.

* visible (default)
내용이 잘리지 않음. 엘리먼트 박스의 범위를 넘어서 보여준다.

* hidden
내용을 자르고, 내용의 나머지는 보여주지 않는다.

* scroll
내용이 잘리지만 남은 내용을 볼 수 있게 하는 스크롤바가 생성된다. (항상 있는)

* auto
내용이 잘리면 남은 내용을 볼 수 있게 하는 스크롤바가 생성된다. (필요시 생성)

* inherit
부모 엘리먼트와 같은 값을 사용한다.

* initial
default value를 사용한다.

visible (default)가 아닌 다른 값으로 overflow 속성 사용 시 새로운 블록 서식 문맥(block formatting context)
를 생성하게 된다.

overflow 속성이 효력을 갖기 위해서는 반드시 블록 레벨 컨테이너의 높이(height 또는 max height)가 설정되어 있거나,
white-space가 nowrap으로 설정되어야 한다. 
