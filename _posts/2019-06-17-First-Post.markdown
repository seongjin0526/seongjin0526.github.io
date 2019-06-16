---
layout: post
title:  "First Post"
date:   2019-06-17 00:09:34 +0900
categories: 포스팅
---

안녕하세요. 깃허브 블로그에는 첫 포스팅이네요.

Jekyll은 어떻게 구축은 했는데 생각보다 에러가 많아서 힘드네요...(포스팅 중에도 에러가...ㅠㅠ)

마크다운을 적용해서 입력하려니 이것도 은근히 일인거같기도하고..(근데 진짜 일하는거 같음)

아무튼 첫글은 앞으로 글을 많이 쓰려하니 마크다운 문법을 공부해봅시다.

\` 이 표시(Back Quote)로 강조를 할 수 있네요. `이렇게`요
그리고 \`이런걸 표시하려면 escape 문자인 \ (Back Slash)를 사용해야합니다.(그냥 코딩인줄?)

마크다운에서 지원하는 코드 하이라이팅 기능이 참 좋네요 '''c <내용> '''  이걸로 감싸도 되고 

\{\% highlight c\%\}
\#include <stdio.h>

int main(){
  printf("Hello World");
  return 0;
}
\{\% endhighlight c\%\}

바로 위처럼 해도됩니다. 그럼 아래처럼 나오겟죠?


{% highlight C %}
#include <stdio.h>

int main(){
  printf("Hello World");
  return 0;
}

{% endhighlight %}

그 다음 링크는 \[링크걸곳\]\(링크 URL\)이렇게 하던가 아니면 \[링크걸곳\]\[링크변수\] 이렇게해서 마지막 아래에 \[링크변수\]: 링크URL
이런식으로 할 수 있네요.

[스틸진의 네이버 블로그](http://blog.naver.com/seongjin0526) 이런식으로요 ㅎ

그럼 밤이 늦었으니 오늘은 여기까지만 하고 나머지는 다른글들을 쓰면서 알아보도록 합시다.

끝.
