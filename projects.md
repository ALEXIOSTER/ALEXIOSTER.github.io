---
layout: default
title: Projects
---

# 🌟 Selected Projects  

Here are some of my best projects.  

{% for project in site.data.projects %}
### 🚀 {{ project.name }}
📝 {{ project.description }}  
🔗 [View on GitHub]({{ project.link }})  
{% endfor %}
