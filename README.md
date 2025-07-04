# 🧮 Calculadora en Python

Este es un trabajo práctico realizado por dos integrantes.
Consiste en una calculadora simple desarrollada en Python que permite realizar operaciones básicas: **suma**, **resta**, **producto** e **impresión de resultados**.

🔗 **Link de referencia (ChatGPT)**:  

---

## 👥 Integrantes

- Persona 1: Ivo Giuliano Cappetto.
- Persona 2: Mateo Lopez.

---

## 📋 Funcionalidades implementadas

- `suma(a, b, c)`: Suma tres números.
- `resta(a, b)`: Resta dos números.
- `producto(a, b)`: Multiplicación de dos números. *(funcionalidad prevista)*
- `imprimir(resultado)`: Impresión de resultados en pantalla. *(actualmente usando `print()` directamente)*

---

## 📘 Historia de usuario

**Como usuario**, quiero poder realizar operaciones básicas como suma y resta desde un programa en Python,  
**para** obtener resultados matemáticos rápidos y precisos de forma sencilla.

---

## ✅ Criterios de aceptación

- El sistema debe tener una función para sumar tres números.
- Debe tener una función para restar dos números.
- El resultado debe mostrarse en consola de manera clara.
- El código debe poder ejecutarse directamente desde `main`.

---

## 📄 Código principal

```python
def suma(a, b, c):
    return a + b + c

def resta(a, b):
    return a - b

if __name__ == "__main__":
    print("Suma:", suma(1, 2, 3))
    print("Resta:", resta(10, 5))
