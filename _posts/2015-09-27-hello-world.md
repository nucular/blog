---
layout: post
title: Hello, World!
subtitle: Subtitle
categories: hello world
---

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

{% highlight py %}
class Greeter(object):
  def __init__(self, greetee):
    # lol greetee
    self.greetee = greetee
  def __str__(self):
    return "Hello, {}!".format(self.greetee)

print(Greeter("World"))
{% endhighlight %}
