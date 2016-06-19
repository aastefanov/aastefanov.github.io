---
layout: page
title: Site.Main()
permalink: /
---
<div class="home">
	<div class="row">
		<div class="col-md-6 col-md-offset-3">

{% highlight csharp %}
class Site
{

	public static void Main()
	{
		User creator = self.creator();
		User client = User.current();
		if(client.hates(creator))
		{
			Leave(DateTime.now);
		}
		else
		{
			Welcome();
		}

		if(client.interestedIn(creator))
		{
			goto About(creator);
		}
	}
}
{% endhighlight %}

		</div>
	</div>
</div>