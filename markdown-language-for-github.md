# Markdown Language for Github
### Markdown 이란?  
가벼운 마크업 언어(Lightweight markup language) 중 하나로, 주요 마크업 언어인 HTML, XML 등보다 문법이 간단하여 이해, 편집 처리하기 쉽다. 
주로 전자 게시판, 블로그나 위키 등에서 복잡한 HTML 대용으로 사용되며 사용자가 글을 읽을 때엔 HTML이나 XHTML로 변환되어 표시된다. 
표준이 없고 모든 HTML 마크업을 대신하지 못하는 것이 단점이다.  
***
## Syntax
```
줄바꿈 : 2 space
문단 바꿈 : 2 enter
*이탤릭체*
**볼드체**
***이탤릭체+볼드체***
~~취소선~~
수평선 : ***
```
***1. HEADERS***
```
# h1
## h2
###### h6
```
```
h1
=====

h2
-----
```

***2. BLOCKQUOTES***
```
> block
> 
> > nested block
>
> back to the first level
```

***3. LISTS***
```
* Red
+ Green
- Blue
```
> * Red
> + Green
> - Blue
```
1. Red
2. Green
3. Blue
3. Yellow
```
> 1. Red
> 2. Green
> 3. Blue
> 3. Yellow

***4. CODE BLOCKS***
```
<pre><code>
your code
</code></pre>
```
```
    your code
    4 space or 1 tab
```
~~~
```language(optional)
your code
```
~~~
```
~~~
your code
~~~
```

***5. CODE***
```
`your code`
```
`your code`

***6. LINKS***
```
[참고1](https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4)
[참고2](https://daringfireball.net/projects/markdown/syntax "마크다운 문법")
<ooheunda@gmail.com>
```
[참고1](https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4)  
[참고2](https://daringfireball.net/projects/markdown/syntax "마크다운 문법")  
<ooheunda@gmail.com>

***7. IMAGES***
```
![재롱이](/img.jpg "재롱이")
```
![재롱이](/img.jpg "재롱이")
***

깃허브를 시작하며 README 파일에 사용되는 Markdown Language를 처음 들어봤고, TIL 작성을 위해 간단히 알아보았다. 
생략한 부분도 있지만 문법은 이 정도만 알아도 문서 작성에 어려움은 없을 것이다. 
작성자 입장에서 가독성이 떨어지는 부분은 있는 것 같다. 그렇지만 HTML만 쓰다가 마크다운을 써 보니 정말 간결하고 좋다!
