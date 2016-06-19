---
layout: page
title: Main()
permalink: /
---
<div class="home">

{% highlight csharp %}
class Site
{
	public static void Main()
	{
		Console.WriteLine("What do you want to do?");
		string action = Console.ReadLine();

		if(action == "F*ck you, mate!")
		{
			Leave(DateTime.now);
		}
	}
}
{% endhighlight %}

</div>