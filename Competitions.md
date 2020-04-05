---
layout: default
title: Robot Game
comments: true
---


<!-- We reopen main-content and container -->

<div class="container-fluid">

    <div class="main-content">



        <!-- Featured
        ==================================================
        <section class="all-posts">

            <div class="section-title text-center">
                <h1>Preparing for Competitions</h1>
            </div>
<br><br><br>
            <div class="row listfeaturedtag">
            {% for post in site.posts %}

                {% if post.tag == "RobotDesigns" %}
                    {% unless post.categories contains "draft" %}

                        {% include featuredbox.html %}
                    {% endunless %}
                {% endif %}

            {% endfor %}
            </div>

        </section>

        <!-- Featured
        ================================================== -->
        <section class="all-posts">

            <div class="section-title text-center">
                <h1>Competition Tutorials</h1>
            </div>
<br><br><br>
            <div class="row listfeaturedtag">
            {% for post in site.posts %}

                {% if post.tag == "Competitions" %}
                    {% unless post.categories contains "draft" %}

                        {% include postlist.html %}
                    {% endunless %}
                {% endif %}

            {% endfor %}
            </div>

        </section>
