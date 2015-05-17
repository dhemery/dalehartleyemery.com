---
title: Connect
layout: about
permalink: /:path/:basename/
links:
-
  name: Email
  url: mailto:dale@dalehartleyemery.com
-
  name: Facebook
  url: http://facebook.com/dalehartleyemery/

-
  name: Twitter
  url: http://twitter.com/dalewriting/

-
  name: Goodreads
  url: https://www.goodreads.com/dalehartleyemery

-
  name: Amazon
  url: https://amazon.com/author/dalehartleyemery
---
{% for link in page.links %}
- [{{ link.name }}]({{ link.url }}){% endfor %}

## Publisher

[Driscoll Brook Press](http://DriscollBrookPress.com)  
PO Box 161924  
Sacramento CA 95816 USA
