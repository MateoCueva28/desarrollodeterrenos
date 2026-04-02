#  Proyecto de Terreno en Unity – Entorno de Bosque
## Realizado por: Mateo Cueva

##  Descripción
Este proyecto consiste en la creación de un entorno 3D interactivo desarrollado en Unity. Se trata de un mundo tipo bosque que incluye montañas, un lago, vegetación, fauna y pequeñas construcciones, permitiendo al usuario explorar libremente el escenario.

---

## Características del entorno

### Terreno
- Terreno principal con textura de césped
- Montañas con diferentes texturas
- Aplicación de textura de nieve en zonas elevadas

### Lago
- Creado mediante modificación del terreno (Lower Terrain)
- Uso de un plano (Plane) con color azul para simular el agua

###  Elementos adicionales
- Casas (assets descargados)
- Árboles (assets descargados)
- Diferentes tipos de vegetación

---

## Fauna
Se incluyeron los siguientes animales:
- Gallina
- Venado
- Perro
- Caballo
- Gato

Los animales cuentan con scripts en C# que permiten movimiento aleatorio dentro del entorno.

---

## Control del jugador
Se implementó un **First Person Controller** que permite recorrer el mundo.

Controles:
- `W, A, S, D` → Movimiento
- `Shift + W` → Movimiento más lento
- `Espacio` → Salto

El usuario puede explorar libremente el entorno, interactuar visualmente con los elementos y recorrer todo el mapa.

---

## Tecnologías utilizadas
- Unity (Motor de desarrollo)
- C# (Scripts de comportamiento)
- Assets descargados desde la Asset Store

---

Cómo ejecutar el proyecto

1. Descargar o clonar este repositorio
2. Abrir Unity Hub
3. Seleccionar **Open Project**
4. Elegir la carpeta del proyecto
5. Ejecutar la escena principal desde Unity

---

Objetivo del proyecto
Crear un entorno 3D inmersivo tipo bosque que permita al usuario explorar un mundo con:
- Relieve variado (montañas y lago)
- Elementos arquitectónicos
- Vegetación
- Fauna con comportamiento dinámico

---
Notas adicionales
Este proyecto fue desarrollado como práctica de diseño de entornos en Unity, integrando assets externos y scripts personalizados.
