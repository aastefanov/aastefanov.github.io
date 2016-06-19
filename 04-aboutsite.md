---
layout: page
title: About(this)
permalink: /about/site
---
<div class="aboutsite">
{% highlight csharp %}

	public static User Site.creator()
	{
		return User::name("Albert Stefanov");
	}

	public static void About(Site site)
	{
		User creator = Site.creator();
		Uri sourceCode = new Uri("https://github.com/aastefanov/aastefanov.github.io/");
	}
	
{% endhighlight %}
</div>