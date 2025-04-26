# 마크다운 문법
1.Heading(제목)
 HTML:<h1>, <h2>, <h3>, ... 

Markdown:
# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목 6

2.Paragraph(문단)
HTML:<p>
Markdawn:줄을 두 번 엔터 치거나 이어서 작성하면 문단이 구분됨.

3.Image(이미지)
HTML:<img src="url" alt="설명">
Markdown:
![설명](이미지URL)

4.Text Style(글자 스타일)
|      |  HTML | Markdown |
|------|-------|----------|
| 굵게  | <strong>, <b> | **굵게**, __굵게__ |
| 기울임 | <em>, <i>     | *기울임*, _기울임_  |
| 취소선 | <del>         | ~~취소선~~        |

5.List(목록)
5-1.Unoredered List(순서 없는 목록)
HTML:<ul>, <li>
Markdown:
- 첫 번째 항목
- 두 번째 항목
  - 하위 항목
5-2.Ordered List(순서 있는 항목)
HTML:<ol>, <li>
Markdown:
1. 첫 번째 항목
2. 두 번째 항목
  1. 하위 첫 번째 항목

6.Link(링크)
HTML:<a href="url">텍스트</a>
Markdown:
[텍스트](URL)

7.Code(코드)
HTML:<code>코드</code>
Markdown:
`코드`

8.Blockquote(인용문)
HTML:<blockquote>내용</blockquote>
Markdown:
> 인용문입니다.
>> 중첩된 인용문입니다.

9.Horizontal Rule(수평선)
HTML:<hr>
Markdown:
--- or *** or ___

10.Table(표)
HTML:<table>, <tr>, <td>
| 제목1 | 제목2 |
|:-----|:------|
| 내용1 | 내용2 |
| 내용3 | 내용4 |

11.Task List(체크박스)
- [ ] 해야 할 일
- [x] 완료한 일
