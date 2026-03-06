# 🐍 Módulo 1 · Python para Data Analysis

Antes de limpiar datos, construir visualizaciones,  
hay algo que tienes que dominar: **hablar con Python**.

Este módulo es ese primer paso. No hay datasets enormes ni visualizaciones complejas todavía — solo tú, Python, y los bloques con los que se construye todo lo demás.

---

## 📁 Qué hay aquí

Siete notebooks. Cada uno ataca un concepto desde cero, con teoría justa y ejercicios progresivos. Sin relleno.

| Archivo | Tema | Qué practicas |
|---|---|---|
| `modulo-1-ejercicio-01-variables.ipynb` | Variables | Tipos de dato, operaciones, comparaciones, input() |
| `modulo-1-ejercicio-02-listas.ipynb` | Listas | Índices, búsqueda, ordenación, copia, métodos |
| `modulo-1-ejercicio-02-tuplas.ipynb` | Tuplas | Inmutabilidad, desempaquetado, zip() |
| `modulo-1-ejercicio-03-diccionarios.ipynb` | Diccionarios | Claves/valores, get(), update(), pop() |
| `modulo-1-ejercicio-03-sets.ipynb` | Sets | Unicidad, operaciones de conjuntos |
| `modulo-1-ejercicio-04-sentencias-control.ipynb` | Control de flujo | if / elif / else, while |
| `modulo-1-ejercicio-05-bucles-for.ipynb` | Bucles | for, range(), list comprehensions |

---

## 🗂️ Cómo está estructurado cada notebook

Todos siguen el mismo esquema para que no tengas que adivinar nada:

```
📌 Qué vas a practicar
🧠 Teoría — solo cuando la necesitas, no toda junta al principio
💻 Ejercicios con enunciados claros y pistas integradas
📋 Tabla resumen al final
```

La teoría aparece justo antes de usarla. Porque leer diez páginas antes de tocar código no funciona.

---

## 🚀 Por dónde empezar

**Lo que necesitas:**
- Python 3.8 o superior
- Jupyter Notebook, JupyterLab o VS Code con la extensión de Python

**Si todavía no tienes Jupyter:**
```bash
pip install jupyter
jupyter notebook
```

**Orden recomendado:**
```
01 Variables → 02 Listas → 02 Tuplas → 03 Diccionarios → 03 Sets → 04 Control → 05 Bucles
```

No saltes de orden si estás empezando. Cada notebook asume que conoces el anterior.

---

## 💡 Convenciones que verás dentro

| Símbolo | Qué significa |
|---|---|
| `# Pista:` | Una ayuda cuando el ejercicio tiene trampa |
| ⚠️ | Error típico de principiante — léelo antes de ejecutar |
| 💡 | Alternativa o curiosidad útil |
| 🌟 `BONUS` | Ejercicio extra si quieres ir más lejos |

---

## 📚 Chuleta rápida

Por si necesitas recordar algo sin abrir el notebook.

### Variables
```python
gatos   = 8           # int
precio  = 9.99        # float
nombre  = "Ana"       # str
activo  = True        # bool

print(f"{nombre} tiene {gatos} gatos")  # f-string — la forma más clara
```

### Listas
```python
colores = ["rojo", "verde", "azul"]
colores[0]          # "rojo"   → primero
colores[-1]         # "azul"   → último
len(colores)        # 3
colores.append("rosa")
```

### Tuplas
```python
persona = (61, 1.54, "pelo marrón")
peso, altura, pelo = persona    # desempaquetado — más limpio que acceder por índice
```

### Diccionarios
```python
d = {"nombre": "Ana", "edad": 25}
d["nombre"]                      # "Ana"
d.get("ciudad", "desconocida")   # sin KeyError si la clave no existe
```

### Sets
```python
s = {1, 2, 3, 3, 2}    # → {1, 2, 3} — los duplicados desaparecen
A & B                    # intersección — lo que tienen en común
A - B                    # diferencia — lo que tiene A pero no B
```

### Control de flujo
```python
if x > 10:
    print("grande")
elif x > 5:
    print("mediano")
else:
    print("pequeño")
```

### Bucles
```python
for i in range(0, 10, 2):                          # 0 2 4 6 8
    print(i)

cuadrados = [x**2 for x in lista]                  # list comprehension
pares     = [x for x in lista if x % 2 == 0]       # con filtro
```

---

*Módulo 1. Cuando acabes aquí, estarás lista para el siguiente.*
