## 자바 스크립트 공부 <br>
**✨ 자바 스크립트 사용 이유 : HTML 조작과 변경** <br>
- document.getElementById('바꾸고싶은 id 이름').innerHTML = '바꾸고싶은 텍스트'; <br>
- document.getElementById('바꾸고싶은 id 이름').style.color = '바꾸고싶은 색상'; <br>
-> 이런 식으로 html 요소의 색상, 사이즈, 마진, 패딩, 내용 등 모든 것 바꾸기 가능

**✨ function : 긴 코드를 깔끔하게 한 단어로 축약하기 위해 사용** <br>
- function 알림창열기(){
			document.getElementById('alert').style.display ='block';
		}

**✨ HTML 요소는 위에 SCRIPT 창은 아래에 / 변경할 HTML 요소가 있으면 그 하단에 JS 작성**

**✨ EventListener**
- document.getElementById('id 이름').addEventListener('click', function(){}); <br>
-> id 이름을 가진 요소를 클릭하면 함수가 실행되게 해주세요. <br>
**✨ EventListener 종류** <br>
- 브라우저 UI와 상호작용 이벤트
1. load : 웹 페이지 로드 완료되었을 때
2. resize : 브라우저 창 크기를 조정했을 때
3. scroll : 사용자가 페이지를 위아래로 스크롤 할 때
- 키보드 이벤트
1. keyup : 사용자가 키를 뗄 때
2. keydown : 사용자가 키를 눌렀을 때
3. keypress : 사용자가 눌렀던 키의 문자가 입력 되었을 때
- 마우스 이벤트
1. click : 사용자가 마우스를 클릭했을 때
2. mouseover : 요소위로 마우스를 움직였을 때


