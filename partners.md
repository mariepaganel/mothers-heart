---
layout: default
title: Партнёры и спонсоры
---
<div class="container-fluid">
    <div class="row">
        {% for item in site.data.partners %}
        <div class="col-md-6 py-1">
            <a style="text-decoration: none" class="card mb-6 box-shadow" target="_blank" href="{{item.url}}" title='{{item.name}}'>
            {%if item.logo%}
                <div class="card-img-top"
                     style="
                             background-image: url('/assets/img/partners/{{item.logo}}');
                             background-size: contain;
                             background-repeat: no-repeat;
                             background-position: center; height: 300px;
                         ">
                </div>
                {%endif%}
                <div class="card-header text-center">{{item.name}}</div>
            </a>
        </div>
        {% endfor %}
    </div>
</div>