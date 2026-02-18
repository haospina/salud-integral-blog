---
layout: default
title: "Ciencias Básicas"
permalink: /categorias/basicas/
nav_order: 1
has_children: true
has_toc: true
---

# 🔬 Ciencias Básicas

## Fundamentos para la Práctica Clínica

Las ciencias básicas constituyen los cimientos del conocimiento médico. 
En esta sección integramos:

### 📚 **Subcategorías:**

1. **Anatomía y Fisiología**
   - Anatomía topográfica y de sistemas
   - Fisiología integrativa
   - Imágenes diagnósticas correlativas

2. **Bioquímica y Biología Molecular**
   - Metabolismo humano
   - Genética médica
   - Farmacología básica

3. **Microbiología y Patología**
   - Agentes infecciosos
   - Respuesta inflamatoria
   - Cambios celulares en enfermedad

### 🎯 **Resultados de aprendizaje**

- Comprende la estructura normal del cuerpo humano
- Entiende los procesos fisiológicos en homeostasis
- Identifica alteraciones a nivel molecular y celular
- Relaciona conocimientos básicos con manifestaciones clínicas

### 📝 **Tipos de Contenido:**

- **Revisiones de tema**: Actualizaciones en ciencias básicas
- **Correlación clínica**: Cómo se aplica en la práctica
- **Casos integradores**: Problemas que requieren conocimiento básico
- **Recursos visuales**: Diagramas, esquemas, infografías

---

**Últimos artículos en esta categoría:**

{% assign basic_posts = site.categories.basicas %}
{% for post in basic_posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d/%m/%Y" }}
{% endfor %}

[Ver todos los artículos de Ciencias Básicas](/categorias/basicas/articulos)
