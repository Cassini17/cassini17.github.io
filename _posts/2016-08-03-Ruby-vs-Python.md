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

The Python version has you importing specific functionality from datetime and dateutil libraries. It’s a lot more explicit, but you can easily tell where everything comes from.

The Ruby version is a lot more magical. We import some active_support library and now all of a sudden all integers in Ruby now have these “.days” and “.from_now” methods. It reads well but it’s definitely not clear where this functionality came from inside of active_support. Plus, the idea of patching all integers in the language with new functionality is cool but it can also be abused and cause problems.

Neither approach is right or wrong, they just emphasize different things. Ruby showcases flexibility of the language while Python showcases directness and readability.

### Web Frameworks

Django and Rails are both frameworks that help you to build web applications. They have similar performance because both Ruby and Python are scripting languages. Each framework provides you all the concepts from traditional MVC frameworks like models, views, controllers, and database migrations.

Each framework has differences in how you implement these features but at the core they are very similar. Python and Ruby also have lots of libraries you can use to add features to your web applications as well. Ruby has a repository called Rubygems that you can use and Python has a repository called the Package Index.

### Community

Python and Ruby both have very large communities behind them. The community influences the direction of the language, updates, and the way software is built using them.

Python has a much more diverse community than Ruby does. There are a ton of academic use cases in both Math and Science that Python has thrived in. This gives it a lot of support in those areas and it continues to grow because of that momentum. Python is also installed on almost every Linux computer making it the perfect language for use on servers.

Ruby’s popularity really started when Rails came out in 2005. The community grew quickly around Rails and has since been incredibly focused on web development. As time goes on it the community around it has gotten much more diverse but2 it hasn’t seen the same diversity that Python has.

### Usage

Who is using these languages? Quite a lot of companies. Both languages and web frameworks are pretty widespread in the tech world.

Python has been by companies including Google, Pinterest, Instagram, National Geographic, Mozilla Firefox, and the Washington Post.

Ruby has been used by companies like Apple, Twitter, Airbnb, Shopify, Github, and Groupon.

### Conclusion

Anything you can do in Ruby on Rails you could also do in Python and Django. Which framework is better isn’t really a question of capability, it’s actually a question of what the support is like for you and your team.

### My general rule of thumb is this:

If you plan on sticking with building web applications, then check out Ruby on Rails. There’s a very strong community built upon it and they are always on the bleeding edge.

If you are interested in building web applications but would like to learn a language that’s used more generally, check out Python and Django. You’ll get a diverse community and lots of influence and support from the various industries that it is used in.

Either way, you can’t go wrong. Almost everything you learn in Python can be translated to Ruby and vice versa. The same goes for Django and Rails. They both have supportive communities behind them. If you have friends doing one or the other, join them because you can always ask them for help along the way.
