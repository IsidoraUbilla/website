# website
https://bootstrapmade.com/demo/Regna/   

# Variables de Lenguaje

Primero obtenemos el lenguaje de la siguiente manera : {% get_current_language as language %}

'''
<div class="p-dropdown">
  <a href="#"><i class="icon-globe"></i><span>{% if language == 'en' %}EN{% else %}ES{% endif %}</span></a>
  <ul class="p-dropdown-content">
    <li><a href="{% url 'lang-redirect' 'es' %}">Spanish</a></li>
    <li><a href="{% url 'lang-redirect' 'en' %}">English</a></li>
  </ul>
</div>
'''
