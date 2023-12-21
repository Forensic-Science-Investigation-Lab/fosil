---
title: Für Studierende
description: Ausschreibungen für Stellen, Praktika und Abschlussarbeiten
layout: page
---

<!--
<table class="table table-sm table-responsive-sm">
        <thead>
            <th scope="col">Thema</th>
            <th scope="col">Typ</th>
            <th scope="col">Voraussetzungen</th>
            <th scope="col">Kontakt</th>
        </thead>
        <tbody id="myTable">
        {% for thesis in site.theses %}
            <tr>
                <td>
                    {{ thesis.title }}
                </td>
                <td>
                    {{ thesis.type }}
                </td>
                <td>
                    {{ thesis.requirements }}
                </td>
                <td>
                    <u><a href="{{ thesis.contact_url | relative_url }}">{{ thesis.contact }}</a></u>
                </td>
            </tr>
            {% endfor %}
        </tbody>
    </table>
-->
<table class="table table-sm table-responsive-sm">
        <tbody id="myTable">
        {% for thesis in site.theses %}
            <tr>
                <td>
                    <a href="{{ thesis.url | relative_url }}">{{ thesis.topic }}</a>
                </td>
            </tr>
            {% endfor %}
        </tbody>
</table>