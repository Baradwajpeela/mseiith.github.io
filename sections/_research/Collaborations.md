---
title: "Collaborations"
layout: post
display: true
---
This page is still under construction!

## Collaborations with Indian institutes, universities and R&D Labs


<ul>
    {% for pro in site.data.col_RD %}

                <li>
                Institute/University/R&D Lab: <strong>{{ pro.lab }}</strong> <br>
                {% if pro.ext %}
                Collaborator: {{pro.ext}} <br>
                {% endif %}
                Faculty: {{pro.fac}} <br>

                </li>
    {% endfor %}
</ul>

## Collaborations with industry


<ul>
    {% for pro in site.data.col_ind %}

                <li>
                Industry/Company: <strong>{{ pro.lab }}</strong> <br>
                Faculty: {{pro.fac}} <br>

                </li>
    {% endfor %}
</ul>


## Collaborations with overseas institutions


<ul>
    {% for pro in site.data.col_over %}

                <li>
                Institute/University: <strong>{{ pro.lab }}</strong> <br>
                {% if pro.ext %}
                Collaborator: {{pro.ext}} <br>
                {% endif %}
                Faculty: {{pro.fac}} <br>


                </li>
    {% endfor %}
</ul>
