---
layout: post
title:  "Self-education is awesome: How to start automate your tests"
date:   2018-02-12 10:37:00 +0000
categories: education, programming, software testing
---
It's crazy how today all knowledge of mankind is available to almost anyone. As long as it's on Google it's just a few clicks away from you. 

Couple of months ago I made my first step to test automation and now I can easily build automation projects from scratch. I realise that there are tons of information to study ahead, that I make mistakes every day, that my yesterday goal seems so small and trivial when I look at it today... but still. 

It's awesome you can study from anywhere in the world and do it for free. StackOverflow, GitHub, Codecademy, Udacity are just a few resources to mention. [This Java course][link1] is the best entry-level programming course I've seen. I really recommend you to start test automation path with Java or Python. You can find lots of useful tutorials and code examples for them. 

As soon as you have a basic knowledge how to write code start with Selenium Webdriver (in [Java][link3] or [Python][link2]) as your main tool for automation testing. There's no alternative for it. But my advice is to switch from pure Selenium to a wrapper like [Selenide][link4]. You'll notice how faster it is to write code in Selenide. Selenide documentation is pretty poor and sometimes you'll need to Google but at the same time, it's very intuitive and self-explanatory. Besides, there are some code examples so you'll have a decent understanding for writing your tests in Selenide.

After that take a quick look at Maven and Gradle. It's always better to build projects with an automation builder instead of downloading all that jars manually. It will save you a lot of time. No big difference what tool you'll use, mostly they have same features.

It's always important to present your test results in a good way. Implementing test reports for a project is quite useful. Go with Surefire and Allure to make test results look fantastic.

Finally, set up Jenkins (or any other CI tool) to make your test runs independent and regular. Jenkins jobs can be configured depending on your needs, including reports generation, email notifications etc.

That was my path in a nutshell. The main idea behind this post is that you don't need a college degree, coding bootcamps or any other kind of paid education. Every bit of information you need is available 24/7 for free and all you need is your time and willingness to learn.

Good luck!

[link1]: https://classroom.udacity.com/courses/ud282
[link2]: http://selenium-python.readthedocs.io/
[link3]: https://www.airpair.com/selenium/posts/selenium-tutorial-with-java
[link4]: http://selenide.org/quick-start.html