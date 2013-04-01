---

layout:default

title:Alex的BLOG

---

##{{page.title}}
最新文章

{% for post in site.posts %}

*	{{ post.date | date_to_string }} [{{site.baseurl}}{{post.url}} {{ post.title }}] 

{% endfor %}