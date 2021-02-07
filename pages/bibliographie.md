---
layout: default
title: Bibliographie
permalink: bibliographie
section: bibliographie
---

L'association Moraine produit un grand nombre de documents (rapports, articles, buletins), conceptualise des panneaux à destination du grand public, mais intervient aussi parfois dans les médias (télévision, radio, etc...).


## Articles

<ul>
    {% for article in site.data.articles %}
    <li>
        <b>
        {{ article.title }}
        </b>
        <br>
        {{article.subtitle }}
        <br>
        <em>
        {{ article.author }}, {{ article.year }}
        </em>
    </li>
    {% endfor %}
</ul>

## Rapports

<ul>
    {% for rapport in site.data.rapports %}
    <li>
        <b>
        {{ rapport.title }}
        </b>
        <br>
        <em>
        {{ rapport.author }}, {{ rapport.year }}
        </em>
    </li>
    {% endfor %}
</ul>

## Bulletins de l'association

<ul>
    {% for bulletin in site.data.bulletins %}
    <li>
        <b>
        {{ bulletin.title }}
        </b>
        <br>
        <em>
        {{ bulletin.author }}, {{ bulletin.year }}
        </em>
    </li>
    {% endfor %}
</ul>

## Panneaux didactiques

<ul>
    {% for panneau in site.data.panneaux %}
    <li>
        <b>
        {{ panneau.title }}
        </b>
        <br>
        <em>
        {{ panneau.author }}, {{ panneau.year }}
        <br>
        <small class="text-muted">{{ panneau.format }}</small>
        </em>
    </li>
    {% endfor %}
</ul>

## Médias

### Magazines
<ul>
    {% for magazine in site.data.magazines %}
    <li>
        <b>
        {{ magazine.magazine }}
        </b>
        <br>
        {{ magazine.title }}
        <br>
        <em>
        {{ magazine.date }}
        </em>
    </li>
    {% endfor %}
</ul>

### Journaux

<ul>
    {% for journal in site.data.journaux %}
    <li>
        <b>
        {{ journal.journal }}
        </b>
        <br>
        {{ journal.title }}
        <br>
        <em>
        {{ journal.date }}
        </em>
    </li>
    {% endfor %}
</ul>

### Télévision

<ul>
    {% for television in site.data.televisions %}
    <li>
        <b>
        {{ television.chaine }}
        </b>
        <br>
        {{ television.title }}
        <br>
        <em>
        {{ television.date }}
        </em>
    </li>
    {% endfor %}
</ul>

### Radio

Divers interviews radio : Sud Radio (du direct), Radio Présence, Radio France, Fréquence Luz, Nostalgie, Radio Montaillou, 100/100, France Inter (Carnets de campagne), RTL (La minute verte)
