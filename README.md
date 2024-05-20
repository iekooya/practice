#제목(header)

# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

# 문장(Paragraph)
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks / 두번 띄어쓰기)
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사<br /> 우리나라 만세

# 강조(Emphasis)

_이탤릭_  
** 두껍게 **  
**_이텔릭+두껍게_**  
~~취소선~~  
<u>밑줄</u>


# 목록(List)
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록


# 링크(Link)
<a herf="https://google.com">GOOGLE</a>  
[GOOGLE](https://google.com)

<a herf="https://www.naver.com" title="NAVER로 이동!">NAVER</a>  
[NAVER](https://www.naver.com "NAVER로 이동!")

# 이미지(Image)
#### ![]()

![HEROPY](https://heropy.blog/css/images/logo.png)

#### 이미지+링크
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog)


# 인용문(BlockQuote)
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중첩된 인용문 1  
>>> 중첩된 인용문 2  
>>> 중첩된 인용문 3


# 인라인(inline) 코드 강조
CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조
```html
<a herf="https://google.com">GOOGLE</a>  
```

```css
.list > li {
  position:absolute;
}
```

```javascript
function func(){
  var a = 'AAA';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
Releative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X


# 원시 HTML (Raw HTML)
동해물과 <span style="text-decoration: underline">백두산</span>이 마르고 닳도록<br />
하느님이 보우하사 우리나라 만세

### a태그에서 target 속성추가
<a herf="https://google.com" target="_blank">GOOGLE</a>  

### 이미지 크기 속성 추가
<img src="https://heropy.blog/css/images/logo.png" width="200">


# 수평선(Horizontal Rule)

---

***
___