# 🐍 Snake Game — React (sin herramientas de build)

Juego clásico Snake implementado con **React vía CDN** y **Babel**, en un único archivo `index.html`.

---

## ¿Cómo jugar?

1. Abre `index.html` en cualquier navegador moderno (sin servidor necesario).
2. Presiona **JUGAR** para comenzar.
3. Usa las **flechas del teclado** para mover la serpiente.
4. Come la comida 🔴 para crecer y sumar puntos.
5. Evita chocar con las paredes o contigo mismo.
6. Cada **50 puntos** la velocidad aumenta (hasta nivel 4).

---

## Estructura de componentes

```
Game            ← contenedor principal, maneja todo el estado
├── Score       ← muestra puntaje y nivel
└── Board       ← tablero del juego
    ├── Snake   ← segmentos de la serpiente
    └── Food    ← celda de comida
```

---

## Tecnologías usadas

- React 18 (CDN)
- Babel Standalone (CDN)
- CSS puro (sin frameworks)

---

## Funcionalidades implementadas

- ✅ Movimiento con flechas del teclado
- ✅ Crecimiento al comer
- ✅ Detección de colisiones (pared y cuerpo)
- ✅ Pantalla de inicio y reinicio
- ✅ Puntaje en tiempo real
- ✅ Sistema de niveles con aumento de velocidad (+5 pts extra)
