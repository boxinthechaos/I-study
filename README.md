# 마크다운이란?
마크다운(MarkDown)은 산문을 읽고, 쓰고, 편집하기 쉬운 목적으로 만들어진 문서 작성을 위한 형식으로 사용되며 문법이 간결하고 HTML삽입이 가능합니다.
이때 마크다운을 작성한 문서의 표현 방식은 CSS의 설정에 따라 달라집니다. 그래서 본 강좌는 깃헙 마크다운 css 기준으로 진행합니다. 따라서 밸로그 마크다운 프리뷰와 약간의 차이가 있을 수도 있습니다.
# 마크다운 문법
## 헤더
* #으로 시작하는 텍스트
* #은 하나부터 여섯개까지 가능
* #이 늘어날때마다 제목의 스케일 낮아집니다
* H1은 ===로도 만들 수 있습니다
* H2sms ---로도 만들 수 있습니다

## Horizontal Rules 수평선
* `-` 또는 *또는_을 3개 이상 작성
* 단,-을 사용할 경우 header로 인식할 수 있으니 이 전 라인은 비워두어야 한다

## Line Breaks 줄바꿈
* `<br>`를 활요해서 줄바꿈을 할 수 있습니다
* 엔터로 칸을 띄면 다음행으로 넘어가게 됩니다. `<br>`은 하나의 문장에서 줄바꿈

## Emphasis 강조
* 기울여 쓰기: *또는_로 감싼 텍스트.
* 두껍게 쓰기: **또는_로 감싼 텍스트
* 취소선 : ~~로 감싼 텍스트
* 이탤릭체와 두껍게를 같이 사용할 수 있습니다

## Blockquotes 인용
* `>`으로 시작하는 텍스트
* `>`는 3개까지 가능합니다
	* 참고로 인용구 안에는 제목이나 리스트, 텍스트박스 등 도 넣을 수 있습니다

## 목록
순서를 표기하는 목록과 순서를 표기하지 않는 목록이 있다
>### 순서를 표기하는 목록
> 숫자와 .을 이용하여 작성한다
<br>
>### 순서를 표기하지 않는 목록
>-,*,+을 사용하여 작성한다

## 인라인 코드
백틱(`)을 사용하여 블록을 씌운다
```
이런식으로 사용 한다
`안녕`
```
`안녕`

## 여러 줄 된 코드 블록
백틱(`) 세 개 사용하여 작성할 수 있다
```
안녕하신가
나는 텅텅이라 하네
```

## 링크
인라인 링크와 url 링크, 참조 링크로 나타낼 수 있습니다.
```
인라인 링크는 아래처럼
[인라인 링크](https://velog.io/)

url 링크는 아래처럼
<https://velog.io/>

참조 링크
[velog]:(https://velog.io/)
```
인라인 링크는 아래처럼
[인라인 링크](https://velog.io/)

url 링크는 아래처럼
<https://velog.io/>

참조 링크
[velog]:(https://velog.io/)

## 수평선
*이나 -, _ 등을 3개 이상 입력하면 작성할 수 있습니다.
띄어쓰기를 중간에 삽입하여도 가능합니다. 다만, 하이픈-은 헤더로 인식할 수도 있으니 주의해서 사용할 필요가 있습니다.

## 이미지 링크
이미지 링크는 아래와 같이 작성할 수 있습니다.
```
![이미지 설명](이미지 링크)
![고양이애옹](https://cdn.pixabay.com/photo/2019/03/13/08/29/cat-4052454_1280.jpg)
```
![이미지 설명](이미지 링크)
![고양이애옹](https://cdn.pixabay.com/photo/2019/03/13/08/29/cat-4052454_1280.jpg)
이미지 크기는 10MB 이하만 가능하다. (gif 포함)
사이즈 조절과 관련된 마크다운은 아직 적용이 되어있지 않은 것 같아요

## 테이블
테이블은 아래와 같이 작성합니다.
| 로 구분하며, <4. 폰트 스타일> 에서 이야기 했던 기본적인 스타일 적용이 가능합니다. 또한 -(하이픈)으로 구분된 곳 각각 왼쪽, 양쪽, 오른쪽에 :(세미콜론)을 붙일 경우 순서대로 왼쪽 정렬, 가운데 정렬, 오른쪽 정렬이 가능합니다.
```
| 이세계 아이돌 이름 | 커버곡 | 개시날자 |
|:-----------------|:------:|--------:|
| 아이네 | God Knows | 2021.11.25 |
| 징버거 | stay | 2023.01.20 |
| 주르르 | 고민중독 | 2024.05.29 |
|  릴파  |  U | 2023.12.3|
| 고세구 | 팬서비스 | 2022.1.11|
|  비챤  | 사랑하긴 했었나요 스쳐가는 인연이었나요 짧지않은 우리 함께했던 시간들이 자꾸 내 마음을 가둬두네 | 2022. 12. 16 |
```
| 이세계 아이돌 이름 | 커버곡 | 개시날자 |
|:-----------------|:------:|--------:|
| 아이네 | God Knows | 2021.11.25  |
| 징버거 | stay | 2023.01.20  |
| 주르르 | 고민중독 | 2024.05.29  |
|  릴파  |  U | 2023.12.3 |
| 고세구 | 팬서비스 | 2022.1.11 |
|  비챤  | 사랑하긴 했었나요 스쳐가는 인연이었나요 짧지않은 우리 함께했던 시간들이 자꾸 내 마음을 가둬두네 | 2022. 12. 16  |

## 체크박스
-, *, + 뒤에 띄어쓰기 후 대괄호를 넣어 작성해주세요. 대괄호안에 띄어쓰기를 하면 빈 체크박스, x를 넣으면 체크된 체크박스가 생깁니다.
```
- [ ] 운동 하기
- [x] 강의 듣기
```
- [ ] 운동 하기
- [x] 강의 듣기

## 이모지
작성된 글 중간중간에 보이는 이모지는 트위터 이모지입니다.
<https://kr.piliapp.com/twitter-symbols/>
아래 주소의 트위터 이모지를 복사 ➜ 붙여넣기 해서 사용하시면 됩니다.
### 단축키
window10: 윈도우 키 + 마침표(.)
mac: Command + Control + 스페이스 바

## 글자 색상
html 태그를 이용하여 작성이 가능합니다.
```
<span style="color:red">red</span>
<span style="color:#d3d3d3">#d3d3d3</span>
<span style="color:rgb(245, 235, 13)">rgb(245, 235, 13)</span>
```
<span style="color:red">red</span>
<span style="color:#d3d3d3">#d3d3d3</span>
<span style="color:rgb(245, 235, 13)">rgb(245, 235, 13)</span>
