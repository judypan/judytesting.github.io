## Introduction

The project is of a piece of very simple (yet correct) C code. We start from posting issues, creating a project, edit the related documentation, code writing, and finally promotion of our project.

## Code

## Contributors

{% for stu in site.stu %}
  <div>
    <img src="{{ stu.image }}" style="display: inline-block; max-width: 50px">
    <span style="font-size: 1.3em">{{ stu.user }} ({{ stu.name }})</span>
    <p>{{ stu.content | markdownify }}</p>
  </div>
{% endfor %}

Repo Last updated: {{ site.time }}
