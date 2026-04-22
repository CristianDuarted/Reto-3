# Reto_3 POO

Este repositorio contiene dos programas hechos en Python para practicar Programación Orientada a Objetos.

---
# 1. Geometría

## Qué hace

Clases principales:

- Point
- Line
- Rectangle

Permite:

- Calcular la longitud de una línea
- Calcular la pendiente en grados
- Detectar si una línea cruza el eje X o Y
- Crear rectángulos de varias formas:
  - Centro + dimensiones
  - Dos puntos
  - Esquina inferior izquierda
  - 4 líneas

## Ejemplo

p1 = Point(2, 3)
p2 = Point(8, 7)

r = Rectangle(point1=p1, point2=p2)

print(r.compute_area())
print(r.compute_perimeter())

---

# 2. Restaurante

## Qué hace

Sistema simple de pedidos.

Clases:

- MenuItem
- Drink
- Appetizer
- MainCourse
- Order

Permite:

- Agregar productos a una orden
- Calcular el total
- Aplicar descuentos:
  - 10% si el total es mayor a 20
  - 20% si el total es mayor a 30
- Mostrar la orden en consola

## Ejemplo

order = Order()

order.add_item(Appetizer("Nachos", 6))
order.add_item(MainCourse("Pizza", 10))
order.add_item(Drink("Coca-Cola", 3, "Grande"))

order.show_order()

## Salida esperada

TU ORDEN:
-------------------
Nachos - $6
Pizza - $10
Coca-Cola (Grande) - $3
-------------------
TOTAL: $17.0

---

# Cómo ejecutar

python main.py

---

# Autor

Cristian Duarte

---

# Notas

Proyecto hecho para practicar:

- Clases
- Herencia
- Composición
- Lógica

---

# Ideas para mejorar

- Crear un menú interactivo
- Guardar órdenes en archivo
- Mejorar la interfaz en consola
