bom
브라우저 오브젝트 모델
dom
문서 오브젝트 모델
bom안에 dom이 포함되어 있다
태크 (엘리멘트) 속성 CSS 자바스크립트 이밴트리스너 콘텐츠

html5의 이벤트는 약 70가지
리스너 앞에 on을 붙인다
onmouseover=가 이벤트리스너의 작성방법
onload
이벤트리스너(이벤트이름,이벤트리스너이름,usecapture)캡쳐하고 버블단계가 있다    
트리를 내려가는 찾아가는 과정을 capture라고 부른다
익명 함수:함수가 필요한데 한 번만 필요할 때 쓰는 이름없는 함수  
이벤트 객체: 이벤트가 일어나는 순간에 만들어지는 객체 function f(e)의 e가 이벤트 객체다 
onclick="return false" href의 이동을 막는다
캡쳐는 원도우에서 출발하고 버블은 원도우로 도착한다
window.onload= function()  
body onload="자바스크립트 코드">
클릭이 포커스 다른 곳을 클릭해서 풀리면 블러 포커스를 얻었을때 발생하는게 onfocus  
onkeydown, onkeypress, onkeyup 키보드를 누를때 뗄떼같은 걸 결정한다  
e.key로 화살표로 상호작용이 가능  
