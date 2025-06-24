```markdown
---
layout: page
title: Publications
permalink: /publications/
---

{% bibliography --cited %}

<!-- Optional: Add custom sections -->
## Journal Articles
{% bibliography --query {type:article} --cited  --sort_by year --reverse %}

## Conference Papers
{% bibliography --query {type:inproceedings} --cited --sort_by year --reverse %}
```
