---
title: Projects
menus:
  main:
    weight: 4
    title: Projects
layout: page
---

# Active Projects

Those are the most relevant projects I'm working on. You can find more at my [GitHub](https://github.com/brunodrugowick).

All projects are integrated with GitHub and are automatically built when merging or commiting (let's not overcomplicate) to master. When relevant I use GitFlow to manage the repository. For example, GraphQL has been added to the development branch/build on [at-the-tsbyss-leaderboard](https://github.com/brunodrugowick/at-the-tsbyss-leaderboard/tree/develop).

| Project       | Description       | GitHub        | App       |
| ------------- | ----------------- | ------------- | --------- | {% for project in site.data.projects %}
| {{ project.name }}  | {{ project.description }} | [GitHub]({{ project.github }}) | {% if project.link != null %} <a href="{{ project.link }}" target="_blank"><img src="/images/angle-double-right-solid.svg" width="20px"/></a> {% endif %} | {% endfor %}
