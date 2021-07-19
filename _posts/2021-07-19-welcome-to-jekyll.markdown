---
layout: post
title:  "한글 가독성 테스트!"
date:   2021-07-19 15:24:03 +0900
categories: jekyll 테스트 
---
이 게시물은 `_posts` 디렉토리에서 찾을 수 있습니다. 계속해서 수정하고 사이트를 다시 빌드하여 변경 사항을 확인하십시오. 여러 가지 방법으로 사이트를 재구축할 수 있지만 가장 일반적인 방법은 'jekyll serve'를 실행하는 것입니다. 이는 웹 서버를 실행하고 파일이 업데이트될 때 사이트를 자동으로 재생성하는 것입니다.

Jekyll은 다음 형식에 따라 블로그 게시물 파일의 이름을 지정해야 합니다.

`YEAR-MONTH-DAY-제목.MARKUP`

여기서 'YEAR'는 4자리 숫자이고 'MONTH'와 'DAY'는 모두 2자리 숫자이며 'MARKUP'은 파일에 사용된 형식을 나타내는 파일 확장자입니다. 그 후 필요한 서론을 포함하십시오. 작동 방식에 대한 아이디어를 얻으려면 이 게시물의 출처를 살펴보세요.

Jekyll은 또한 코드 조각에 대한 강력한 지원을 제공합니다.

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

{% highlight java %}
public void testJavaCode(){
  HashMap<string, string> test = new HashMap<>();
}
{% endhighlight %}

Jekyll을 최대한 활용하는 방법에 대한 자세한 내용은 [Jekyll 문서][jekyll-docs]를 참조하세요. 모든 버그/기능 요청은 [Jekyll's GitHub repo][jekyll-gh]에 제출하세요. 궁금한 사항은 [지킬톡][지킬톡]으로 문의주세요.

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
