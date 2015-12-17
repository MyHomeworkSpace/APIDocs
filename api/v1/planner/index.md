---
title: /api/v1/planner
layout: layout
categories: [ apiv1 ]
---

Check version information of the Planner API. This also can be used to check if the API is available and responding.

### Parameters
None.

### Returns
A JSON object with the following properties:

* status - always "ok".
* version - always "1".

### Example response
{% highlight javascript %}
{
	"status": "ok",
	"version": "1"
}
{% endhighlight %}