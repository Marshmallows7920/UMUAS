---
layout: post
title: Our Sponsorships
description: Our Sponsorships
image:
nav-menu: true
---

<!-- Two -->
<div style="border-radius: 25px; padding-top: 10px; padding-bottom: 10px; background-color: #f0ffff; align-items: center; display: flex; flex-wrap: wrap; justify-content: space-around;" class="image-list">
        {% for image in site.static_files %}
            {% if image.path contains 'images/SponsorLogos' %}
                <div style="margin-top: 5px; margin-bottom: 5px; flex-basis:30%;" class="sub-image">
                    <img style="margin-left: auto;margin-right: auto; width: 90%;" src="{{ image.path }}" alt="image"/>
                </div>
            {% endif %}
        {% endfor %}
</div>

<div style="margin-top: 50px;">
    <h2>
        Sponsorships Package
    </h2>
    <img style="display: block; margin-left: auto;margin-right: auto; width: 90%;" src="/assets/images/SponsorPackage.PNG" alt="image"/>
</div>

