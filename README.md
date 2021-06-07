---
title: Title test
---

# micro-down



**1.3kB** JavaScript markdown parser
  [view on GitHub](https://github.com/shynrou/micro-down)

```ruby
def print_hi(name)
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



[Root File]({{site.baseurl}}/file)
