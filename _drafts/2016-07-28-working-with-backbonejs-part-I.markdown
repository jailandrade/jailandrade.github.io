---
layout: post
title:  "Working with backbone.js part I"
date:   2016-07-28 00:50:52 -0500
categories: javascript, backbone.js
---

It's a Javascript tool to structure web applications and provide some adventages against build code from zero like backbone.js still a option in 2016?

Yes. It does.

And I want to experiment with backbone.js 

This is a guide to build a form html with backbone.js First we need to setup the html document.

{% highlight html %}
<!doctype html>
<html>
<head>
</head>
<body>
    <div class="page">
        <form method="post" action="">
            <input type="text" placeholder="Nombre" name="name">
            <input type="email" placeholder="Email" name="email">
            <input type="password" placeholder="Password" name="password">
            <input type="submit" value="Enviar">
        </form>
    </div>
</body>
</html>
{% endhighlight %}