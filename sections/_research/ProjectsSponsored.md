---
title: " Projects - Sponsored"
layout: projectLay
display: true
---

This page is under construction~.

## Ongoing Projects


<ol reversed>
    {% for pro in site.data.projects_ongoing %}

                <li>
                Title: <strong>{{ pro.title }}</strong> <br>
                PI: {{pro.PI}} <br>

                {% if pro.CoPI %}
                Co-PI: {{pro.CoPI}} <br>
                {% endif %}
                Funding agency: {{pro. FundAgn}} <br>
                Duration: {{pro.Duration}} <br>

                </li>
    {% endfor %}
</ol>

## Completed Projects


<ol reversed>
    {% for proCom in site.data.projects_completed %}

                <li>
                Title: <strong>{{ proCom.title }}</strong> <br>
                PI: {{proCom.PI}} <br>

                {% if prproComo.CoPI %}
                Co-PI: {{proCom.CoPI}} <br>
                {% endif %}
                Funding agency: {{proCom. FundAgn}} <br>
                Duration: {{proCom.Duration}} <br>

                </li>
    {% endfor %}
</ol>
