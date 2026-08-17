# NYC Aug 2026 🗽

Itinerario interactivo para un viaje de 10 días a Nueva York (18-27 agosto 2026).

## Planning actual

- **Hotel:** The Hotel At Fifth Avenue — 3 E 40th St (Midtown East, junto a Bryant Park y Grand Central)
- **Llegada:** martes 18, JFK a las 22:00 · **Vuelta:** jueves 27, vuelo a las 23:00
- **Ritmo:** despertar a las 9:00, salir sobre las 9:45, desayuno siempre fuera del hotel

### Entradas con hora fija

| Día | Hora | Actividad |
|-----|------|-----------|
| Mié 19 | 10:30 | Empire State Building |
| Jue 20 | 11:00 | American Museum of Natural History |
| Dom 23 | 17:00 | Moulin Rouge! (Al Hirschfeld Theatre) |
| Mié 26 | 16:30 | Circle Line — Liberty Midtown Cruise (Pier 83) |

Además: **lunes 24 a las 7:00** alarma para las entradas gratuitas del 9/11 Museum (franja 17:00
del mismo día), y **martes 25** excursión de día completo a Washington DC en Amtrak.

## Funcionalidades

- **Itinerario día a día** — 10 días con timeline hora a hora, expandible por actividad
- Badge **🎟️ HORA FIJA** en las actividades con entrada u hora cerrada
- **Reservas** — checklist con persistencia en localStorage, barra de progreso, links directos
- **Info práctica** — hotel, entradas, distancias a pie, comer barato, presupuesto, propinas, apps
- Tema oscuro · Mobile-first · Sin dependencias (solo Google Fonts)
- Swipe horizontal entre días
- Auto-selección del día actual dentro del rango del viaje
- Indicador "AHORA" en la franja horaria activa
- Links a Google Maps en cada actividad

## GitHub Pages

1. Crea un repo en GitHub y sube este directorio
2. Settings → Pages → Source: `main` branch, `/ (root)`
3. Accede a `https://<usuario>.github.io/<repo>/`

## Estructura

```
index.html   ← app completa (HTML + CSS + JS embebidos)
README.md
```

Para editar el planning, toca los arrays `DAYS`, `RESERVAS` e `INFO` al principio del `<script>`
de `index.html`.
