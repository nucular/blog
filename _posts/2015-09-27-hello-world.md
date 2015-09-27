---
layout: post
---

Hello, World!
=============

It works!

{% highlight py %}
class Greeter(object):
  def __init__(self, greetee):
    # lol greetee
    self.greetee = greetee
  def __str__(self):
    return "Hello, {}!".format(self.greetee)

print(Greeter("World"))
{% endhighlight %}
