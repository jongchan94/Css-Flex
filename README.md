# Css-Flex-Grid-

<포토 리스트>

이미지를 깨지지않게 위해 flex-shrink: 0

/* 글자수에 따라서 이미지가 작아짐 기본값이 쉬링크 1*/
flex-shrink: 0;

<유저 리스트>
/줄 넘기 안되고 줄임표 표시/
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;

<카드 리스트>
이미지를 직접 태그해서 넣는것보다 
백그라운드이미지로 삽입하는것이 컨트롤 하기가 더쉽다.
카드 리스트의 이미지는
일반적으로 db에 있는 이미지를 불러오기 때문에
인라인 css로 넣는 것이 합리적이다.
