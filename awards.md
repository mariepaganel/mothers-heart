---
layout: default
title: Награды
---
<div class="album py-5 bg-light">
    <div class="container-fluid">
        <div class="row">
            {% for i in (1..69) %}
                <div class="col-md-4">
                    <a style="text-decoration: none" class="card mb-4 box-shadow" target="_blank" href="/assets/img/awards/{{i}}.jpg">
                        <div class="card-img-top"
                             style="
                                     background-image: url('/assets/img/awards/{{i}}.jpg');
                                     background-size: cover;
                                     background-position: center; min-height: 350px;
                                 "></div>
                    </a>
                </div>
            {% endfor %}
        </div>
    </div>
</div>