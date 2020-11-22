---
title: "Awards"
layout: projectLay
display: true
---

This page is under construction~.

## Faculty awards and recognition


<ol>
    {% for pro in site.data.award_fac %}

                <li>

                {{pro.fac}}, <strong>{{ pro.title }}</strong>  ({{pro.dur}}) <br>

                {% if pro.info %}
                Info: {{pro.info}} <br>
                {% endif %}

                </li>
    {% endfor %}
</ol>

## Student awards


<ol reversed>
    {% for pro in site.data.award_stu %}

                <li>

                {{pro.stu}}, <strong>{{ pro.title }}</strong>  ({{pro.dur}}) <br>

                {% if pro.info %}
                Info: {{pro.info}} <br>
                {% endif %}

                </li>
    {% endfor %}
</ol>
