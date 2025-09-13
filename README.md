
# RepoPhyton

Repositorio de Prácticas en Python

---

## Descripción

Este repositorio contiene ejemplos y ejercicios básicos en Python para quienes están comenzando en el mundo de la programación. Aquí encontrarás código sencillo, explicaciones y diagramas para ayudarte a entender cómo funcionan los programas.

---

## Diagrama de Flujo Básico

A continuación, se muestra un diagrama de flujo simple para un programa que pide al usuario un número y muestra si es par o impar:

```mermaid
flowchart TD
	A[Inicio] --> B[Pedir número al usuario]
	B --> C{¿El número es par?}
	C -- Sí --> D[Mostrar "Es par"]
	C -- No --> E[Mostrar "Es impar"]
	D --> F[Fin]
	E --> F[Fin]
```

---

## Ejemplo Sencillo de Código

### Ejemplo 1: Verificar si un número es par o impar

```python
# Solicita un número al usuario
numero = int(input("Ingresa un número: "))

# Verifica si el número es par o impar
if numero % 2 == 0:
	print("El número es par")
else:
	print("El número es impar")
```

### Ejemplo 2: Sumar dos números

```python
# Solicita dos números al usuario
a = int(input("Ingresa el primer número: "))
b = int(input("Ingresa el segundo número: "))

# Suma los números y muestra el resultado
suma = a + b
print("La suma es:", suma)
```

---

## ¿Cómo empezar?

1. Instala Python desde [python.org](https://www.python.org/downloads/).
2. Clona este repositorio:
   ```bash
   git clone https://github.com/TuUsuario/RepoPhyton.git
   ```
3. Abre los archivos `.py` y prueba los ejemplos.

---

## Recursos útiles

- [Documentación oficial de Python](https://docs.python.org/es/3/)
- [Curso Python para principiantes (YouTube)](https://www.youtube.com/results?search_query=python+para+principiantes)

---

#### Futuro programador 🚀
