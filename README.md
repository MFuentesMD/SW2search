# SW2search: rastreador Switch 2 Zelda 40 aniversario (Chile)

Tarea programada de Claude Code que busca en tiendas chilenas confiables:

- **Consola Nintendo Switch 2, edición Zelda 40 aniversario** (el juego no viene incluido)
- **Pro Controller, edición Zelda 40 aniversario**
- *(Opcional, de colección)* **Zelda: Ocarina of Time** para Switch 2 en formato físico

Compara precios, revisa el stock y avisa por **correo a marcelofuentes@me.com**, con enlace directo para comprar, y con una **notificación push** en la app de Claude.

## Cómo funciona
- **Frecuencia:** cada 2 horas, de 07:xx a 23:xx (hora de Chile).
- **Alerta 🚨:** se envía solo cuando hay novedades (stock nuevo a precio razonable o una baja de precio de 5 % o más).
- **Resumen diario 📊:** se envía en la corrida de las ~21:00 con la tabla comparativa completa.
- **Estado entre corridas:** cada corrida lee el último correo enviado para comparar precios.
- **Instrucciones completas:** [`tarea/prompt.md`](tarea/prompt.md) (umbrales de precio, tiendas confiables y reglas).
- **Datos de partida:** [`tarea/linea-base-2026-11-06.md`](tarea/linea-base-2026-11-06.md).

## Ajustes rápidos
Para cambiar los umbrales, la frecuencia o pausar la tarea, pídeselo a Claude en esta sesión. La tarea está en claude.ai/code → Scheduled tasks.

## Conector Gmail
El conector Gmail ya está agregado a la tarea (6-nov-2026). Si alguna corrida no puede usarlo, entrega sus hallazgos por notificación push (en la línea que empieza con "SIN GMAIL:").
