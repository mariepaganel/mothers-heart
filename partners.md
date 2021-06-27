---
layout: default
title: Партнёры и спонсоры
---
<div class="container-fluid">
    <div class="row">
        {% for item in site.data.partners %}
        <div class="col-md-6 py-1">
            <a href="{{item.url}}">
                <img class="img-fluid" style="max-height: 300px" src='/assets/img/partners/{{item.logo}}' title='{{item.name}}' alt='{{item.name}}'>
            </a>
        </div>
        {% endfor %}
    </div>
</div>