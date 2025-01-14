# Reto_05

## Modulo Unico: 

En este enfoque, se crea un único paquete que contiene un solo módulo. Este módulo incluye todas las clases relacionadas con formas geométricas (`shape`). 

**Estructura del Proyecto:**

```
Only_Shape/
│   ├── __pycache_  _/
│   ├── shapes_package/
│   ├── __init__.py
│   ├── shape.py
└── main.py

```

- `Only_Shape/`: Carpeta raíz del proyecto.
- `__pycache__/`: Carpeta generada automáticamente por Python para almacenar archivos `.pyc` compilados.
- `shapes_package/`: Paquete que contiene el módulo `shape.py` con todas las clases de formas geométricas.
- `main.py`: Archivo principal donde se instancian y se usan las clases definidas en el módulo `shape.py`.


---

## Módulos Individuales:

En este enfoque, se crea un paquete con diferentes módulos, cada uno destinado a una forma geométrica específica.
**Estructura del Proyecto:**


```
shape/
├── shape_modular/
│   ├── __pycache__/
│   ├── __init__.py
│   ├── equilateral.py
│   ├── isosceles.py
│   ├── line.py
│   ├── point.py
│   ├── rectangle.py
│   ├── RightTriangle.py
│   ├── scalene.py
│   ├── square.py
│   └── triangle.py
└── main.py
```

- `shape/`: Carpeta raíz del paquete que contiene todos los módulos relacionados con las formas geométricas.
- `shapes_modular/`: Subcarpeta que contiene los módulos específicos para cada forma geométrica.
- `__pycache__/`: Carpeta generada automáticamente por Python para almacenar los archivos `.pyc` compilados.
- `main.py`: Archivo principal donde se importa y utiliza cada módulo individual para crear y manipular formas geométricas.

Cada archivo dentro de `shapes_modular/` contiene clases específicas para representar y trabajar con diferentes tipos de formas geométricas.

---
