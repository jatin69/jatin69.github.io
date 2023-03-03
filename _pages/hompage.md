---
layout: homepage
title: Home
permalink: /
---

<div class="col-md-2"></div>
<div class="col-md-8">
    <header class="post-header text-center">
        <img style="width: 15em; height: 15em; border-radius: 50%;"
            src="{{site.baseurl}}/images/{{site.profilePicture}}">
        <h1 style="font-size: 3em; font-family: Raleway;">Jatin Rohilla</h1>
        {% if site.facebook %}
        <a target="_blank" href="{{site.facebook}}">
            <li class="social twitter"><i class="fa fa-facebook-square"></i></li>
        </a>
        {% endif %}
        {% if site.twitter %}
        <a target="_blank" href="{{site.twitter}}">
            <li class="social twitter"><i class="fa fa-twitter-square"></i></li>
        </a>
        {% endif %}
        {% if site.github %}
        <a target="_blank" href="{{site.github}}">
            <li class="social github"><i class="fa fa-github-square"></i></li>
        </a>
        {% endif %}
        {% if site.linkedin %}
        <a target="_blank" href="{{site.linkedin}}">
            <li class="social linkedin"><i class="fa fa-linkedin-square"></i></li>
        </a>
        {% endif %}
        {% if site.email %}
        <a target="_blank" href="mailto:{{site.email}}">
            <li class="social email"><i class="fa fa-envelope"></i></li>
        </a>
        {% endif %}
    </header>
    <div style="margin: 2em 0em 2em 0em; text-align: left;">
        <p>
            Hello! I'm Jatin Rohilla. Currently, I'm an SDE 2 at Amazon India. I'm passionate about software engineering, and web development. 
        </p>
            I completed my MCA in 2020 from Department of Computer Science, University of Delhi. Prior to that, in 2017, i completed my BSc. (Hons.) Computer Science from Deen Dayal Upadhyaya College, University of Delhi. I did a few projects during my college time, check them out under <a href="/projects">Projects</a>. More details can be found on my github. 
        <p>
            
        </p>
        <!-- <p>Here's my <a href="/resume">Resume</a> (Last updated a long time ago). </p> -->
    </div>
</div>
<div class="col-md-2"></div>
