# 🧠 Reto_3 POO 

Este repo tiene **dos programas** hechos en Python para practicar Programación Orientada a Objetos.

---

# 📐 1. Geometría

## 🧩 Qué hace

Hay clases para trabajar con cosas geométricas:

- `Point`
- `Line`
- `Rectangle`

Con esto puedes:

- Calcular la longitud de una línea
- Sacar la pendiente (en grados)
- Ver si una línea cruza el eje X o Y
- Crear rectángulos de varias formas:
  - con centro, ancho y alto
  - con dos puntos
  - con esquina inferior izquierda
  - con 4 líneas

---

## Ejemplo

```python
p1 = Point(2, 3)
p2 = Point(8, 7)

r = Rectangle(point1=p1, point2=p2)

print(r.compute_area())
print(r.compute_perimeter())
