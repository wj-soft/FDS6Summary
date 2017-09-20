## 인기 사이트

· q 태그
	- 둘러싼 텍스트가 짧은 인라인 인용문이라는 것을 나타낼 때 사용한다.
	- 단락 구분이 필요한 긴 인용문은 blockquote 태그를 사용할 것.

	· cite
	- 이 속성의 값은 인용된 정보의 원본 문서나 메세지를 가르키는 URL을 나타냄.
	ex) <p cite="해당 원본 문서 사이트명"> 인용문 </q>


· counter
	- counter(name, style)
	- name은 카운터의 이름, style은 기본값은 10진수인 decimal 선택값은 아래 속성 중에 선택할 것.
	- style 종류
		disc, circle, square, decimal, decimal-leading-zero, lower-roman, upper-roman,m lower-greek, lower-latin, upper-latin, armenian
		georgian, lower-alpha, upper-alpha, none.

	ex)
		.favorite-list li {
		  counter-increment: number;
		}

		.favorite-list li::before {
		  content: counter(number, decimal);
		}


· transform
	- 엘리먼트에 적용될 변환을 지정한다.
	- 몇 가지 변환을 공백으로 구분하여 순서대로 지정해 놓음으로써 여러가지 변환을 동시에 적용할 수 있다.

	· translate
	- 개체의 위치를 옮길 수 있다. 주어진 크기만큼 위치가 조정 된다.
	ex) transform : translate(20px, 10px);
		- transform: translateX(value);
		- transform: translateY(value);

	· rotate
	- 개체를 주어진 각도로 회전 시킬 수 있다.
	ex) transform : rotate(45deg); ==> 시계방향으로 45도 기울임

	· scale
	- 개체의 크기를 조절 할 수 있다.
	ex) transform : scale(1.5); ==> 1.5배 커짐

	· skew
	- 개체를 주어진 각도로 기울일 수 있다.
	ex) transform:skew(10deg, 10deg)
		- 첫번째 10deg는 좌우로 기울이는 효과
		- 두번째 10deg는 앞뒤로 기울이는 효과

