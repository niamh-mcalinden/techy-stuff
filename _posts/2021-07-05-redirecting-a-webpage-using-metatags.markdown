---
layout: default
title:  "Redirecting a webpage using meta tags"
date:   2021-07-05 15:56:37 +0100
categories: jekyll update
---
Metadata is what happens behind the website, It can be used to take us to a different webpage and can be used for other stuff aswell. In this case we are using it to take us to a new page!

{% highlight html %}
<!DOCTYPE HTML>
<html lang="en">
<head>
<meta charset="UTF-8">
--Metadata to be added here--

<meta name="viewport"
content="width=device-width, initial-scale=1">
<meta http-equiv="refresh"
content="5 ; url='URL TO BE INSERTED HERE'">
<title>Refresh this page</title>
<head>
<body>
<h1>
</body>
</head>
{% endhighlight %}

# meta http-equiv

By refreshing the page the URL you wrote in the 'meta http-equiv' section should come up and you will be able to see that website.