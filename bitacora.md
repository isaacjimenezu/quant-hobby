# Bitácora del hobby quant

## Módulo 1 · Semana 1 (13–18 nov 2026)

**Qué aprendí:**
- Aprendí (más bien recordé o reaprendí) a usar las lubrerías numpy y pandas
- Aprendí que resolver ejercicios de quant interview questions es muy entretenido
- Aprendí (recordé) sobre esperanza de varias variables
- Aprendí que los rendimientos diarios lineales no se suman en el tiempo, los logaritmicos sí y ayudan a dar el rendimiento logaritmico anual
- Aprendí qué son los ETFs y cuales son los más populares

**Qué me sorprendió:**
- Me sorprendió que puedo recordar cosas de programación o probabilidad con facilidad
- Me sorprendió la manera de resolver ejercicios de probabilidad con python

**Qué quiero probar:**
- Quiero probar que puedo reaprender python y probabilidad
- Qué ETFs de los 10 fue el más volatil

**Pregunta de la semana:** ¿El 14.8 % anual de SPY en los últimos 10 años es una buena estimación de lo que rendirá en los próximos 10?
- El promedio nos serviría. Si suponemos que el promedio es ese 14.8%, entonces más bien mientras mayor sea el periodo de tiempo, mejor podríamos aproximar la media ya que crece a ritmo más rápido que la volatilidad. En el caso de 10 años, domina la tendencia.
- Ahora, no saber el promedio puede implicar que el promedio se ubica entre 14.8%+-6%. Ese es un rango grande. Entonces no nos da una buena estimación para los próximos 10 sin saber el promedio.

## Módulo 1 · Semana 2 (18–20 nov 2026)

**Qué aprendí:**
- Aprendí por qué los precios de algunas ETFs están ajustados. La razón de fondo son los dividendos. Hay unos ETFs que no pagan dividendos y por eso no se ajustan. Yahoo ajusta los precios del pasado para que los rendimientos los incluyan. GLD no paga dividendos, por eso su precio no se ajusta; y como cada dividendo nuevo modifica todos los precios anteriores, el precio de una fecha pasada depende de cuándo bajes los datos.
- La autocorrelación te dijo que a los días malos de SPY les suelen seguir rebotes, y eso explicaba por qué la volatilidad mensual salía más baja.
- Aprendí a usar resample
- Aprendí que es la autocorrelación

**Qué me sorprendió:**
- Me sorprendió la volatilidad de los ETFs, en particular el de los bonds a largo plazo

**Qué quiero probar:**
- ¿Hay algún ETF, o alguna frecuencia, donde los rendimientos se parezcan a una normal?

**Pregunta de la semana:** Encontraste 38 días en que SPY se movió más de 4 sigmas, cuando una normal predice 0.3. Si alguien te dice "la volatilidad de SPY es de 19 %, así que es muy raro perder más de 5 % en un día", ¿qué le contestarías y por qué?
- Contestaría que sí es raro. Esto es porque recordemos que la sigma de la SPY es 0.0121. Es decir 1.21%. Decir que pierda (baje) 5% es que se mueva más de 4 sigmas. La realidad es que sí es raro, solo pasó 38 veces desde 2006. De 2006 a 2026 hay alrededor de 252*21 = 5000+250+40+2 = 5292 días. Pasó 38/5292 < 0.6% de los días. Entonces sí lo considero como que es algo raro que pase.
- Es raro, pero mucho menos raro de lo que la volatilidad sugiere, y por qué eso importa

