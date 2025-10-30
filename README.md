# Zyfra, Aprendizaje supervisado y tratamiento de datos

📖 Resúmen:  
  Necesitamos formatear. limpiar y eficientar la base de datos para poder crear un modelo predictivo confiable para la empresa Zyfra dedicada al desarrollo de soluciones de eficiencia para la industria pesada.
.  
.  
.  
🎯 Objetivo:  
  Mediante un modelo predictivo obtener información que permita predecir la cantidad de oro extraído de el mineral de oro.

❌ Problema:  
  Amplia base de datos con bastantes valores ausentes o incoherentes.

✅ Solución:  
  Limpiamos y tratamos de forma efectiva datos según su naturaleza y creamos un modelo predictivo preciso.

🔢 Metodologia:  
  1. Análisis y formateo de datos.  
  2. Comprobación de datos correctos mediante formula de recuperación de oro del primer proceso.
  3. Reordenamiento de columnas según su lugar en el proceso.
  4. Eliminación de valores ausentes en columnas críticas del proceso y eliminación de valores incongruentes del proceso.
  5. Tratamiento de valores ausentes que no pueden ser eliminados mediante reemplazo de valores a "0", reemplazo de valores con la mediana, interpolación lineal y calculo de resultado con formula de recuperación final del oro.
  6. Analizamos y presentamos visualmente las tendencias de los metales principales (au, ag, pb, sol).
  7. Creación, validación y elección de modelos mediante validación cruzada (árbol de decisión, bosque aleatorio y regresión lineal).
  8. Prueba de modelo final con métrica SMAPE y muestra de conclusiones.

📊 Conclusiones:  
  Creación de un modelo exitoso, tan solo se equivoca el 1.18 veces de cada 100 predicciones (métrica SMAPE final).
