# noticias.md

Resumen diario de noticias de mercado, en español.

Cada día de mercado hay un archivo con lo más importante de la sesión: qué se movió, por qué y qué viene. Está pensado para leerse en cinco minutos.

Para ver los gráficos y los datos de los valores que se citan, usa TRAMUNT: [cheery-florentine-99bae4.netlify.app](https://cheery-florentine-99bae4.netlify.app).

> **No es asesoramiento financiero.** Estos resúmenes son informativos. No recomiendan comprar ni vender nada. Comprueba siempre los datos en la fuente original antes de tomar una decisión.

## Estructura

Un archivo por día, agrupado por año y mes:

```
2026/
  11/
    2026-11-13.md
    2026-11-14.md
```

El nombre es la fecha en formato `AAAA-MM-DD`, en hora de España. Los fines de semana y los festivos sin mercado no llevan archivo.

## Formato de cada resumen

```markdown
# Resumen de mercado: AAAA-MM-DD

## En una frase
Lo más importante del día.

## Índices
| Mercado | Cierre | Variación |
|---|---|---|
| S&P 500 | … | +0,0 % |

## Lo que movió el mercado
- Noticia, con su efecto en el mercado y la fuente.

## Empresas
- Resultados, operaciones y movimientos destacados.

## Divisas, materias primas y cripto
- EUR/USD, petróleo, oro, bitcoin…

## Agenda de mañana
- Datos macro, resultados y bancos centrales.

## Fuentes
- Enlace a cada fuente citada.
```

Si un día no hay nada que contar en una sección, quítala.

## Criterios

- **Hechos con fuente.** Cada noticia lleva su enlace. Si algo es una opinión o un rumor, se dice.
- **Cifras con su contexto.** Variaciones en porcentaje, con signo (+/−), y la hora o el cierre al que se refieren.
- **Español de España**, con frases cortas y sin jerga cuando haya una alternativa.
- **Corto.** Mejor tres noticias bien contadas que diez listadas.
