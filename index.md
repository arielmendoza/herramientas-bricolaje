---
layout: home
---

# 🛠️ Las mejores herramientas para bricolaje

{% for post in site.posts limit:5 %}
## [{{ post.title }}]({{ post.url }})
![{{ post.title }}]({{ post.featured_image }}){:.tool-image}
**Valoración**: {{ post.rating }}/5  
[Leer reseña →]({{ post.url }}){:.btn}
{% endfor %}

[Ver todas las reseñas](/archivo.html){:.btn .btn-primary}
