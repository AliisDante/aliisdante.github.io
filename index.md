---
layout: default
---

Hi! I'm Isaac.

I'm not really sure what to do with this blog yet but I want to share more about the stuff I'm learning while also practising writing as a skill. I promise not to use AI to write my stuff -- after all, how am I supposed to practise writing if AI does it for me?? XD

I'm also kinda practising Markdown so please forgive any formatting mistakes.

Thank you!

# Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }}) on {{ post.date | date_to_long_string: "ordinal" }}

{% endfor %}
