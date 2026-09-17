# combat-arena

Arena de combate 2D hecha en **Godot 4.7**. Una pantalla, oleadas de enemigos y un combate
centrado en el *feel*: combo cancelable, esquiva con invulnerabilidad y **parry** con ventana de tiempo.

> Estado: **en desarrollo**. Aquí irá el GIF cuando el combate esté en pie.

## Controles

| Acción | Tecla |
|---|---|
| Moverse | A / D o flechas |
| Atacar | J o clic izquierdo |
| Esquivar | Espacio |
| Parry | K o clic derecho |

## Qué demuestra

- **Combate**: máquina de estados del jugador, combos con cancelación, ventanas de invulnerabilidad y de parry
- **Game feel**: *hitstop*, temblor de pantalla, partículas y sonido en cada impacto
- **Bucle completo**: oleadas, muerte, reinicio, puntuación y mejor marca

## Hoja de ruta

- [ ] 1. Un golpe que mata a un muñeco quieto
- [ ] 2. *Hitstop* y temblor de pantalla
- [ ] 3. Un enemigo que avisa y golpea
- [ ] 4. Esquiva y parry
- [ ] 5. Cinco oleadas y puntuación
- [ ] 6. Sonido, pulido y publicar en itch.io

Fuera de alcance hasta la 1.0: jefes, progresión, tienda, varios escenarios, historia y 3D.

## Cómo abrirlo

1. Godot **4.7** → *Import* → elegir `project.godot`
2. Escena principal: `scenes/main.tscn`

## Estructura

```
scenes/    escenas .tscn
scripts/   scripts .gd
assets/    sprites y sonidos
```

## Licencia

MIT (ver `LICENSE`).
