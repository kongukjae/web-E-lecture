
## step 별 설명

- step-1
자바스크립트 알고리즘 작성을 최대한 줄이기 위해 임의의 class를 선정하여 작업하는 방식을 채택했다. 알고리즘에는 .hidden이라는 클래스를 동적으로 추가하고 삭제하는 방식으로만 알고리즘을 짠다면, hidden 클래스 안에 설정된 attribute display:none;이 적용되는 방식이 되어 안보이게 될 것이다. 

- step-2
자바스크립트 부분에서 알고리즘을 선택할 대상을 초기화(init) 해준다.
이때 querySelector() 라는 메서드와 모든 셀렉터를 배열로 가져오겠다는
querySelectorAll() <-- All 이 붙은 메서드를 혼동하여선 안된다.
초기화 작업이 제대로 진행되지 않으면 알고리즘 작업에서 추적하기 어려우므로 반드시 디버깅을 진행하여 제대로 식별했는지 확인한다.

- step-3

웹페이지가 로드(접속)되었을 때는 컨텐츠 내용 두가지중 한가지가 보이지 않은 상태여야 하기 때문에, 마크업을 통해 hidden 클래스를 2번 컨텐츠 내용부분에 할당해준다.

- step-4

1. 탭메뉴버튼 1번을 눌럿을때 2번 컨텐츠 내용 태그에 class = hidden이 부여된 상태여야한다. 를 작성해준다.
1-1. 이벤트리스너 메서드를 사용한다.

1-2. 안티패턴이긴하나, 명시적으로 확인을 해야하기 때문에 식별자와 타겟의 알고리즘을 읽어볼수 있게 작성한 내용이므로 다음 페이지에서 깔끔한 코드를 확인할 것 

1-3 페이지 뷰에서 실제로 어떻게 동작하는지 원리를 추적할 것