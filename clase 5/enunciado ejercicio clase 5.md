## Ejercicio: Linealización y ajuste exponencial

Para poner un poco en práctica las cosas que estuvimos viendo sobre regresiones lineales vamos a trabajar con datos reales sobre consumo energético de fuentes renovables. El objetivo del ejercicio va a ser visualizar los datos, ajustar un modelo exponencial a las observaciones, evaluar su validez y automatizar el análisis.

### Consignas / guía

1. Descarguen el dataset desde la página web de
   [Our World in Data](https://ourworldindata.org/grapher/global-energy-substitution?time=earliest..2024) y levántenlo como un dataframe.

2. Exploren gráficamente la evolución del consumo energético para las fuentes renovables del dataset (Biofuels, Solar, Wind, Other renewables). 

3. Elijan una de esas fuentes y ajuesten un modelo exponencial del tipo
   $$
   E(t) = a \cdot e^{bt}
   $$
   donde $E(t)$ representa el consumo de la fuente elegida en función del tiempo.

4. Evalúen el ajuste gráficamente y con las métricas que vimos en clase. ¿Les parece razonable el modelo?

5. Generalicen el proceso para todas las fuentes: escriban una función que, dada una fuente, devuelva los coeficientes del ajuste y alguna métrica de calidad, y apliquen esa función al dataset completo usando alguna herramienta de programación funcional 

**Nota:** Este punteo no es más que una guía de los pasos que pueden seguir para analizar un dataset como este, pero siéntanse libres de calcular y graficar los estadísticos que le parezcan más interesantes.
