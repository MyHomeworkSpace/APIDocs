---
title: /api/v1/planner/announcements/get
layout: layout
categories: [ apiv1 ]
---

Gets a list of features enabled on the account.

### Parameters
* `date` - the date to check for an announcement. Provided in the URL.

### Returns
A JSON object with the following properties:

* status - "ok" if the operation was successful, or "error" if there was a problem.
* announcement - A JavaScript object if there is an announcement, or `null`.

### Example response
{% highlight javascript %}
{
	"status": "ok",
	"announcement": {
		"text": "Some important announcement"
	}
}
{% endhighlight %}