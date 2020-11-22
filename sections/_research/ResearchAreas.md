---
title: "Research Areas"
layout: post
display: true
---

### Department is actively pursuing research in the following major domains

- [Structural materials](#structural-materials)
- [Functional Materials](#functional-materials)
- [Computational Materials Science](#computational-materials-science)
- [Healthcare and Bio-Materials](#healthcare-and-bio-materials)
- [Nanoscience and Nanotechnology](#nanoscience-and-nanotechnology)

## Structural Materials
<ul>
    {% for res in site.data.resArea_Struc %}

                <li>
                <strong>{{ res.area }}</strong> <br>
                Faculty working in this area:<br> <a href="{{ res.fac1_lnk }}" target="_blank" class="faculty-link">{{res.fac1}}</a>,

                {% if res.fac2 %}
                <a href="{{ res.fac2_lnk }}" target="_blank" class="faculty-link">{{res.fac2}}</a>,
                {% endif %}
                {% if res.fac3 %}
                <a href="{{ res.fac3_lnk }}" target="_blank" class="faculty-link">{{res.fac3}}</a>,
                {% endif %}
                {% if res.fac4 %}
                <a href="{{ res.fac4_lnk }}" target="_blank" class="faculty-link">{{res.fac4}}</a>,
                {% endif %}
                {% if res.fac5 %}
                <a href="{{ res.fac5_lnk }}" target="_blank" class="faculty-link">{{res.fac5}}</a>.
                {% endif %}
                </li>
    {% endfor %}
</ul>

## Functional Materials
<ul>
    {% for res in site.data.resArea_Func %}

                <li>
                <strong>{{ res.area }}</strong> <br>
                Faculty working in this area:<br> <a href="{{ res.fac1_lnk }}" target="_blank" class="faculty-link">{{res.fac1}}</a>,

                {% if res.fac2 %}
                <a href="{{ res.fac2_lnk }}" target="_blank" class="faculty-link">{{res.fac2}}</a>,
                {% endif %}
                {% if res.fac3 %}
                <a href="{{ res.fac3_lnk }}" target="_blank" class="faculty-link">{{res.fac3}}</a>,
                {% endif %}
                {% if res.fac4 %}
                <a href="{{ res.fac4_lnk }}" target="_blank" class="faculty-link">{{res.fac4}}</a>,
                {% endif %}
                {% if res.fac5 %}
                <a href="{{ res.fac5_lnk }}" target="_blank" class="faculty-link">{{res.fac5}}</a>.
                {% endif %}
                </li>
    {% endfor %}
</ul>


## Computational Materials Science
<ul>
    {% for res in site.data.resArea_Comp %}

                <li>
                <strong>{{ res.area }}</strong> <br>
                Faculty working in this area:<br> <a href="{{ res.fac1_lnk }}" target="_blank" class="faculty-link">{{res.fac1}}</a>,

                {% if res.fac2 %}
                <a href="{{ res.fac2_lnk }}" target="_blank" class="faculty-link">{{res.fac2}}</a>,
                {% endif %}
                {% if res.fac3 %}
                <a href="{{ res.fac3_lnk }}" target="_blank" class="faculty-link">{{res.fac3}}</a>,
                {% endif %}
                {% if res.fac4 %}
                <a href="{{ res.fac4_lnk }}" target="_blank" class="faculty-link">{{res.fac4}}</a>,
                {% endif %}
                {% if res.fac5 %}
                <a href="{{ res.fac5_lnk }}" target="_blank" class="faculty-link">{{res.fac5}}</a>.
                {% endif %}
                </li>
    {% endfor %}
</ul>

## Healthcare and Bio-Materials
<ul>
    {% for res in site.data.resArea_health %}

                <li>
                <strong>{{ res.area }}</strong> <br>
                Faculty working in this area:<br> <a href="{{ res.fac1_lnk }}" target="_blank" class="faculty-link">{{res.fac1}}</a>,

                {% if res.fac2 %}
                <a href="{{ res.fac2_lnk }}" target="_blank" class="faculty-link">{{res.fac2}}</a>,
                {% endif %}
                {% if res.fac3 %}
                <a href="{{ res.fac3_lnk }}" target="_blank" class="faculty-link">{{res.fac3}}</a>,
                {% endif %}
                {% if res.fac4 %}
                <a href="{{ res.fac4_lnk }}" target="_blank" class="faculty-link">{{res.fac4}}</a>,
                {% endif %}
                {% if res.fac5 %}
                <a href="{{ res.fac5_lnk }}" target="_blank" class="faculty-link">{{res.fac5}}</a>.
                {% endif %}
                </li>
    {% endfor %}
</ul>

## Energy Materials
<ul>
    {% for res in site.data.resArea_energy %}

                <li>
                <strong>{{ res.area }}</strong> <br>
                Faculty working in this area:<br> <a href="{{ res.fac1_lnk }}" target="_blank" class="faculty-link">{{res.fac1}}</a>,

                {% if res.fac2 %}
                <a href="{{ res.fac2_lnk }}" target="_blank" class="faculty-link">{{res.fac2}}</a>,
                {% endif %}
                {% if res.fac3 %}
                <a href="{{ res.fac3_lnk }}" target="_blank" class="faculty-link">{{res.fac3}}</a>,
                {% endif %}
                {% if res.fac4 %}
                <a href="{{ res.fac4_lnk }}" target="_blank" class="faculty-link">{{res.fac4}}</a>,
                {% endif %}
                {% if res.fac5 %}
                <a href="{{ res.fac5_lnk }}" target="_blank" class="faculty-link">{{res.fac5}}</a>.
                {% endif %}
                {% if res.fac6 %}
                <a href="{{ res.fac6_lnk }}" target="_blank" class="faculty-link">{{res.fac6}}</a>.
                {% endif %}
                {% if res.fac7 %}
                <a href="{{ res.fac7_lnk }}" target="_blank" class="faculty-link">{{res.fac7}}</a>.
                {% endif %}
                {% if res.fac8 %}
                <a href="{{ res.fac8_lnk }}" target="_blank" class="faculty-link">{{res.fac8}}</a>.
                {% endif %}
                {% if res.fac9 %}
                <a href="{{ res.fac9_lnk }}" target="_blank" class="faculty-link">{{res.fac9}}</a>.
                {% endif %}
                </li>
    {% endfor %}
</ul>

## Nanoscience and Nanotechnology
<ul>
    {% for res in site.data.resArea_Nano %}

                <li>
                <strong>{{ res.area }}</strong> <br>
                Faculty working in this area:<br> <a href="{{ res.fac1_lnk }}" target="_blank" class="faculty-link">{{res.fac1}}</a>,

                {% if res.fac2 %}
                <a href="{{ res.fac2_lnk }}" target="_blank" class="faculty-link">{{res.fac2}}</a>,
                {% endif %}
                {% if res.fac3 %}
                <a href="{{ res.fac3_lnk }}" target="_blank" class="faculty-link">{{res.fac3}}</a>,
                {% endif %}
                {% if res.fac4 %}
                <a href="{{ res.fac4_lnk }}" target="_blank" class="faculty-link">{{res.fac4}}</a>,
                {% endif %}
                {% if res.fac5 %}
                <a href="{{ res.fac5_lnk }}" target="_blank" class="faculty-link">{{res.fac5}}</a>.
                {% endif %}
                {% if res.fac6 %}
                <a href="{{ res.fac6_lnk }}" target="_blank" class="faculty-link">{{res.fac6}}</a>.
                {% endif %}
                {% if res.fac7 %}
                <a href="{{ res.fac7_lnk }}" target="_blank" class="faculty-link">{{res.fac7}}</a>.
                {% endif %}
                {% if res.fac8 %}
                <a href="{{ res.fac8_lnk }}" target="_blank" class="faculty-link">{{res.fac8}}</a>.
                {% endif %}
                {% if res.fac9 %}
                <a href="{{ res.fac9_lnk }}" target="_blank" class="faculty-link">{{res.fac9}}</a>.
                {% endif %}
                </li>
    {% endfor %}
</ul>
