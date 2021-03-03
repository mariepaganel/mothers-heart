---
layout: default
title: Контакты
subtitle: Мы на связи!
---
## Карельский региональный благотворительный фонд “Материнское сердце”

Фактический/Почтовый адрес: Республика Карелия, г. Петрозаводск, ул. Горького, д.25 оф.38 (4 этаж)

Тел.: 8 (8142) 59-35-05

E-mail - bfond10@mail.ru, daridobro@onego.ru

<div class="row">
  {% for person in site.data.people %}
	  <div class="col-lg-4">
	    <img class="rounded-circle" src="{% if person.avatar %}{{ person.avatar }}{% else %}/assets/img/avatar.png{% endif %}" alt="аватар" width="140" height="140">
	    <h2>{{ person. name }}</h2>
	    <p>{{ person.title }}</p>
	  </div><!-- /.col-lg-4 -->
  {% endfor %}
</div>
