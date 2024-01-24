## JavaScript <br>
**✨ 자바 스크립트 사용 이유 : HTML 조작과 변경** <br>
```document.getElementById('바꾸고싶은 id 이름').innerHTML = '바꾸고싶은 텍스트';``` <br>
```document.getElementById('바꾸고싶은 id 이름').style.color = '바꾸고싶은 색상';``` <br>
-> 이런 식으로 html 요소의 색상, 사이즈, 마진, 패딩, 내용 등 모든 것 바꾸기 가능

**✨ function : 긴 코드를 깔끔하게 한 단어로 축약하기 위해 사용** <br>
```function 알림창열기(){document.getElementById('alert').style.display ='block';}```

**✨ HTML 요소는 위에 SCRIPT 창은 아래에 / 변경할 HTML 요소가 있으면 그 하단에 JS 작성**

**✨ EventListener** <br>
```document.getElementById('id 이름').addEventListener('click', function(){});``` <br>
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

## **jQuery** <br>
**✨ jQuery 사용 이유 : 브라우저 호환성, 간편한 DOM 조작, 애니메이션 및 효과, AJAX 요청의 단순화, 사용이 간편하고 빠른 개발 등**
- jQuery 파일 첨부한 곳 밑에서부터 jQuery 문법 작성 가능(body 태그 끝나기 전 쪽에 작성하는 것이 좋음! 그냥 모든 js 파일 다 넣기) <br>
```$('#test')``` : id가 test인 요소 선택 <br>
```$('.test')``` : class가 test인 요소 선택
- html 요소 바꾸는 법(오른쪽이 jQuery 문법!) <br>
```document.getElementById('test').innerHTML = '안녕';``` == ```$('#test').html('안녕');```
- css 적용하는 법 <br>
```$('#test').css('color', 'pink');``` -> css('이걸', '이렇게')

**✨ jQuery 문법 종류** <br>
1. after : 해당 요소 뒤에 내용 추가 -> ```$('#test').after('안녕');```
2. before : 해당 요소 앞에 내용 추가 -> ```$('#test').before('안녕');```
3. html : 해당 요소의 내용 변경 -> ```$('#test').html('안녕하세요');```
4. prepend : 선택 요소의 자식 요소의 맨 앞에 내용을 추가 -> ```$('#test').prepend('반갑습니다');```
5. append : 선택 요소의 자식 요소의 맨 뒤에 내용을 추가 -> ```$('#test').append('안녕히계세요';)```
6. remove : 태그를 포함한 요소 전체를 제거 -> ```$('#test').remove();```
7. empty : 선택 요소의 내용(text)만을 제거 -> ```$('#test').empty();```
- toggle : 'show'라는 class가 있으면 제거, 없으면 추가 <br>
```document.getElementsByClassName('list-group')[0].classList.toggle('show');```

## **✨ Selector 선택자** <br>
**✨ Selector 사용 이유 : DOM(Document Object Model)을 사용하여 HTML 문서의 요소에 접근하고 조작할 수 있게 해주고, 각각의 메서드는 특정 조건에 맞는 요소를 선택하여 JavaScript를 통해 동적인 변경이나 상호작용을 할 수 있도록 함**
**✨ Selector 종류** <br>
1. getElementById('id명')
2. getElementsByClassName('class명')[선택 요소 인덱스] <br>
-> id 선택에는 Element! class 선택에는 Elements! s 기억하기/'' 사이에 .이나 # 안붙이고 클래스명, 아이디명 작성
3. querySelector('.class명')
4. querySelectorAll('.class명')[선택 요소 인덱스] <br>
-> 클래스 선택자: .className
-> 아이디 선택자: #idName
  
