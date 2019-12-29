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
            Hello World!
            I'm currently a final semester MCA student at Department of Computer Science, University of Delhi. 
            I'm also an upcoming SDE Intern and FTE at Amazon India. 
        </p>
        <p>
            I'm passionate about web and software development. If you're interested in knowing about my technical experience, checkout my <a href="/projects">Projects</a>. 
        </p>
        <!-- <p>Here's my <a href="/resume">Resume</a>. </p> -->
    </div>
</div>
<div class="col-md-2"></div>
