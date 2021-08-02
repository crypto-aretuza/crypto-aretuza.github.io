---
layout: page
title: odbiorcy
permalink: /odbiorcy/
---

<h3>
    <a href="{{ site.baseurl }}/wizerunek">wizerunek</a> &nbsp; &nbsp;
    <a href="{{ site.baseurl }}/odbiorcy">odbiorcy</a> &nbsp; &nbsp;
    <a href="{{ site.baseurl }}/kanaly">kanały</a> &nbsp; &nbsp;
    <a href="{{ site.baseurl }}/zasoby">zasoby</a> &nbsp; &nbsp;
    <a href="{{ site.baseurl }}/pop">marketing</a> &nbsp; &nbsp;
</h3>

### odbiorcy

chcemy dotrzeć do następujących grup:

<ul>
    <li> potencjalni pracownicy </li>
    <li> studenci </li>
    <li> licealiści </li>
    <li> nauczyciele </li>
    <li> świat </li>
</ul>

<div class="posts">
  {% for post in site.categories.odbiorcy %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">więcej</a>
    </article>
  {% endfor %}
</div>

### potencjalni pracownicy

ludzie po studiach matematycznych, informatycznych, telekomunikacyjnych.

wartość dla nas:
<ul>
    <li> ciekawi ludzie dowiadują się o możliwości pracy u nas </li>
    <li> większy rynek, większy wybór </li>
</ul>

wartość dla nich:
<ul>
    <li> dowiadują się o możliwości ciekawej pracy </li>
    <li> wiedząc czym się zajmujemy, mogą zdecydować czy to ich interesuje </li>
</ul>

kanały komunikacji z nimi:
<ul>
    <li> strona internetowa popularyzująca kryptografię </li>
    <li> strona internetowa z zadaniami, które trzeba zrobić przed rekrutacją </li>
</ul>

### studenci

studenci kierunków matematycznych, informatycznych, telekomunikacyjnych.

wartość dla nas:
<ul>
    <li> wzrost zainteresowania kryptogarfią w Polsce </li>
    <li> możliwość współpracy z ośrodkami naukowymi i badawczymi </li>
    <li> możliwość zatrudnienia pracowników z większą wiedzą na temat kryptografii </li>
    <li> ciekawi ludzie dowiadują się o możliwości pracy u nas </li>
</ul>

wartość dla nich:
<ul>
    <li> wysokiej jakości materiały do nauki kryptografii w języku polskim </li>
    <li> dowiadują się o możliwości ciekawej pracy </li>
</ul>

kanały komunikacji z nimi:
<ul>
    <li> strona internetowa popularyzująca kryptografię </li>
    <li> strona internetowa z zadaniami, które trzeba zrobić przed rekrutacją </li>
</ul>

### licealiści

### nauczyciele akademiccy

wartość dla nas:
<ul>
    <li> pośredni wpływ na program na uczelniach (udostępnianie materiałów, stworzenie skryptu) </li>
</ul>

wartość dla nich:
<ul>
    <li> dostęp do materiałów dydaktycznych wysokiej jakości </li>
    <li> możliwość wykorzystania darmowych materiałów (np. zadań programistycznych na laboratoria) </li>
</ul>

#### świat
