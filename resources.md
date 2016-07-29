---
layout: page
title: Diabetes Resources
permalink: /diabetes-resources/
---
The below information is a compilation of all the information I have learned and gathered as I have 
struggled with beating my Type 2 Diabetes.  Please keep in mind that this is merely an opinion blog.  It is the story of my struggle with Type 2 Diabetes and what has worked for me.  I am not a doctor 
or a registered dietician.  Please read the full <a href="{{ site.baseurl }}/disclaimer">disclaimer</a>.
<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>