---
layout: post
title: Our Sponsorships
description: Our Sponsorships
image:
nav-menu: true
---


<style>
    .logo-container{
        border-radius: 25px; padding-top: 10px; padding-bottom: 10px; background-color: #f0ffff; align-items: center; display: flex; flex-wrap: wrap; justify-content: space-around;
    }

    .sponsor-logo{
        margin-top: 5px; margin-bottom: 5px; flex-basis:25%;
    }

    @media only screen and (max-width: 600px) {
        .sponsor-logo {
            flex-basis:40%;
        }
    }

    @media only screen and (min-width: 600px) and (max-width: 1200px){
        .sponsor-logo {
            flex-basis:30%;
        }
    }
</style>

<!-- Two -->
<div class="logo-container">
        {% for image in site.static_files %}
            {% if image.path contains 'images/SponsorLogos' %}
                <div class="sponsor-logo">
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

