---
title: "Projects - Consultancy"
layout: post
display: true
---
This page is still under construction!

## Ongoing Projects


<ol reversed>
    {% for pro in site.data.Project_indus_onConsult %}

                <li>
                Title: <strong>{{ pro.title }}</strong> <br>
                PI: {{pro.PI}} <br>

                {% if pro.CoPI %}
                Co-PI: {{pro.CoPI}} <br>
                {% endif %}
                Industry/Company: {{pro. FundAgn}} <br>
                Duration: {{pro.Duration}} <br>

                </li>
    {% endfor %}
</ol>

## Completed Projects


<ol reversed>
    {% for proCom in site.data.Project_indus_ComConsult %}

                <li>
                Title: <strong>{{ proCom.title }}</strong> <br>
                PI: {{proCom.PI}} <br>

                {% if prproComo.CoPI %}
                Co-PI: {{proCom.CoPI}} <br>
                {% endif %}
                Industry/Company: {{proCom. FundAgn}} <br>
                Duration: {{proCom.Duration}} <br>

                </li>
    {% endfor %}
</ol>
