# 🧛‍♂️ UTroid – Pygame Edition

Juego estilo **Vampire Survivors** desarrollado en **Python con Pygame**.  
El personaje dispara automáticamente y el objetivo es sobrevivir el mayor tiempo posible mientras derrotás enemigos y acumulás puntos.

---

## 🎮 Características

- 🔫 Disparo automático
- ⌨ Movimiento con teclas **WASD**
- 👾 Enemigos por rondas progresivas
- 💠 Sistema de esferas de puntuación
- 🏆 Puntaje máximo guardado
- ❤️ Sistema de 3 vidas
- 🛡 Escudo de invulnerabilidad temporal (5 segundos)

---

## 🕹 Cómo se juega

- **Moverse:** `W` `A` `S` `D`
- El personaje **dispara automáticamente**
- Cada enemigo eliminado deja una **esfera**
- Las esferas se cuentan al finalizar la partida
- El puntaje se suma al **puntaje máximo global**
- El high score se puede consultar desde el **menú principal**

---

## 👾 Sistema de Rondas

- Cada ronda dura **10 segundos**
- En cada nueva ronda:
  - Se **duplica** la cantidad de enemigos respecto a la ronda anterior
- La dificultad aumenta progresivamente

Ejemplo:

- Ronda 1 → 5 enemigos  
- Ronda 2 → 10 enemigos  
- Ronda 3 → 20 enemigos  
- Ronda 4 → 40 enemigos  

---

## ❤️ Sistema de Vidas

- Tenés **3 vidas**
- Cada vez que un enemigo te toca:
  - Perdés 1 vida
  - Se activa un **escudo de invulnerabilidad** por 5 segundos
- Al perder las 3 vidas:
  - Termina la partida
  - Se cuentan las esferas recolectadas

---

## 💻 Requisitos

Necesitás:

- 🐍 **Python 3**
- 🧠 **Visual Studio Code**
- 📦 **Pygame**

---

## ⚙ Instalación y ejecución

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
```
2️⃣ Abrir el proyecto

Arrastrar la carpeta del proyecto dentro de Visual Studio Code

3️⃣ Instalar dependencias (si es necesario)
pip install pygame

4️⃣ Ejecutar el juego

Click derecho en main.py

Seleccionar Run Python File

Se abrirá el menú principal 🎮
