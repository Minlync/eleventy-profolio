---
title: project
layout: uiux.njk
tags: navItem

---
<main class="uiux">{% for page in collections.design %}
     <div class="pjcard">
        <a href="/#"></a>
       <img src="/images/{{page.data.postImg}}" alt="{{page.data.postImgAlt}}">
       <div class="card_text">
         <h3> <a href="{{page.url}}">{{page.data.title}}</a></h3> 
        <p>{{page.data.Time}} </p>
       <p>{{page.data.Location}}<p> 
         </div>
      </div>{% endfor %}
     
   </main>