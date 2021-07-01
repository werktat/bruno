---
layout: default
title: TestBlog
---
# micro-down4
{:.no_toc}

This is an abstract of the article. It serves the purpose to
show a quick overview.

## Table of Contents
{:.no_toc}

* TOC
{:toc}

[Root File]({{site.baseurl}}/file)
[Contents](./file)


<ul>
{% for item in site.data.yamldata.bikes %}
<li>{{item.title}}</li>
{% endfor %}
</ul>

  <ol>
    {% assign items = site.chapters | sort: 'weight' %}
    {% for post in items %}
      <li>
        
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        
      </li>
    {% endfor %}
  </ol>

<svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg" width="80" height="80" colors="#a3a948,#edb92e,#f85931,#ce1836,#009989" name="Felisa Rincon" size="80"><mask id="mask__bauhaus" maskUnits="userSpaceOnUse" x="0" y="0" width="80" height="80"><rect width="80" height="80" rx="40" fill="#fff"></rect></mask><g mask="url(#mask__bauhaus)"><rect width="80" height="80" rx="40" fill="#a3a948"></rect><rect x="10" y="30" width="80" height="80" fill="#edb92e" transform="translate(4 -4) rotate(330 40 40)"></rect><circle cx="40" cy="40" fill="#f85931" r="16" transform="translate(18 18)"></circle><line x1="0" y1="40" x2="80" y2="40" stroke-width="2" stroke="#ce1836" transform="translate(0 0) rotate(300 40 40)"></line></g></svg>

# Jekyll Blog Demo 🧪 📝 🚀
> Starter for a static website or blog - built with Jekyll, a minimal theme and GH Pages

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/jekyll-blog-demo?include_prereleases&sort=semver)](https://GitHub.com/MichaelCurrin/jekyll-blog-demo/tags/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Jekyll](https://img.shields.io/badge/Jekyll-3.9-blue?logo=jekyll&logoColor=white)](https://jekyllrb.com)
[![Made with Minima](https://img.shields.io/badge/minima-2.5-blue?logo=ruby)](https://github.com/jekyll/minima)

[![Hosted with - GitHub Pages](https://img.shields.io/badge/Hosted_with-GitHub_Pages-blue?logo=github&logoColor=white)](https://pages.github.com/)


## Preview

[![Sample screenshot](/sample.png "Sample screenshot")](https://michaelcurrin.github.io/jekyll-blog-demo/)


## How to use this project

<div align="center">

[![Site link](https://img.shields.io/badge/View_site-Jekyll_Blog_Demo-blue?style=for-the-badge)](https://michaelcurrin.github.io/jekyll-blog-demo/)

[![Use this template](https://img.shields.io/badge/Generate-Use_this_Template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/jekyll-blog-demo/generate)

</div>

This project was generated using the Jekyll CLi for a starting point. Now IT includes a demo of Jekyll _Collections_ too. See the _Languages_ section on the site, the `languages.md` file and the `_languages` directory. 


## Documentation

<div align="center">

[![view - Documentation](https://img.shields.io/badge/view-Project_docs-blue?style=for-the-badge)](/docs/)

</div>


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).

**1.3kB** JavaScript markdown parser
  [view on GitHub](https://github.com/shynrou/micro-down)

```ruby
df print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

```javascript
function sayHello(name) {
  if (!name) {
    console.log('Hello World');
  } else {
    console.log(`Hello ${name}`);
  }
}
```

{% highlight ruby linenos %}
def foo
  puts 'foo'
end
{% endhighlight %}

## Inline Markup

_italic:_ \*italic\* \_italic\_

__bold:__ `**bold** __bold__`

___bold italic:___ `***bold italic*** ___bold italic___`

```
code: `code`
```

~underline:~ `~underline~`

~~strike through:~~ `~~strike through~~`

~~~deleted:~~~ `~~~deleted~~~`


## Blocks

``` not_javascript
Pre
formatted
```

``` not_javascript
Pre
  formatted
    blocks
    can
    be defined
  with ``` surrounding them,
  they can also receive classes.
  
	Tabs work here too!
```

> Block quotes can also be handy.
>   They are very nice to get some interresting content
>

> "Blocks in general support _~inline~_ __styles__"




## Media
### Links
``` markdown
[github](http://github.com Just a hover text!)
or simply as URL via auto linking https://github.com/commit-intl/micro-down
```
[github](http://github.com Just a hover text!)
  or simply as URL via auto linking https://github.com/commit-intl/micro-down

### Images
``` markdown
![github](https://raw.githubusercontent.com/commit-intl/micro-down/master/microdown.svg micro-down logo)
```
![github](https://raw.githubusercontent.com/commit-intl/micro-down/master/microdown.svg micro-down logo)

combined:
``` markdown
[![github](https://raw.githubusercontent.com/commit-intl/micro-down/master/microdown.svg micro-down logo)](http://github.com Just a hover text!)
```
[![github](https://raw.githubusercontent.com/commit-intl/micro-down/master/microdown.svg micro-down logo)](http://github.com Just a hover text!)

## lists

1. Lists can be structured and layered
  1. like this
  2. for example
2. __and can also be mixed__
	- like
	+ this
3. _~inline works here to~_
   and can be quite handy


## Table

|-this   -|-is     -|-a  -
| really  | useless | table
| even more | useless | row

| this   | is also    |  quite useless
|---
| but images, links and code works here too | ![micro-down logo](https://raw.githubusercontent.com/commit-intl/micro-down/master/microdown.svg) | [micro-down logo](https://raw.githubusercontent.com/commit-intl/micro-down/master/microdown.svg)
| fancy you know | `![micro-down logo](https://raw.githubusercontent.com/commit-intl/micro-down/master/microdown.svg)` | `[micro-down logo](https://raw.githubusercontent.com/commit-intl/micro-down/master/microdown.svg)`



