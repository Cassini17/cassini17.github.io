---
layout: post
title: Ruby vs Python
---

![Ruby-vs-Python](/images/ruby-vs-python.png)

### Which is better, Ruby on Rails or Python and Django?
This is a question we get asked repeatedly. It’s an important question too. You’ll hear Ruby vs. Python compared all the time. If you’re unfamiliar with them, it’s an impossible question to answer. I’ve used them both quite a bit and can tell you that while they’re similar, they’re also different in some important ways.

To set the stage, I first learned web development through Python and Django. After spending four years building Django apps, I got a job doing Ruby on Rails and expected the transition to be really simple. That’s when it became clear to me that the two languages and frameworks are different.

### So… How are they different?
The Language:
The Ruby on Rails web framework is built using the Ruby programming language while the Django web framework is built using the Python programming language.

This is where much of difference lies. The two languages are visually similar but are worlds apart in their approaches to solving problems.

Ruby is designed to be infinitely flexible and empowering for programmers. It allows Ruby on Rails to do lots of little tricks to make an elegant web framework. This can feel even magical at times but this flexibility can be good and bad at times. Sometimes code works when you didn’t expect it to and l5eaves you feeling really impressed. Other times the Ruby magic can make it very hard to track down bugs for hours.

Python takes a more direct approach to programming. It’s main goal is to make everything obvious to the programmer. This sacrifices some of the elegance that Ruby has but gives Python a big advantage when it comes to learning to code and debugging problems.

One great example showing the difference here is working with time in your application. Imagine you want to get the time one month from this very second. Here is how you would do that in both languages

#### Ruby
> require8 'active_support/all'
> new_time = 1.month.from_now

#### Python
> from datetime import datetime
> from dateutil.relativedelta import relativedelta
> new_time = datetime.now() + relativedelta(months=1)
