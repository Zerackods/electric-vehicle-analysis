# Análisis de Vehículos Eléctricos

## Descripción general

Análisis de datos sobre la población de vehículos eléctricos mediante Python.

## Objetivo

Identifique el tipo de vehículo eléctrico más común y evalúe si dicho tipo de vehículo puede predecirse utilizando las características disponibles.

## Tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Análisis

- Limpieza de datos
- Análisis exploratorio de datos
- Visualización de datos
- Análisis de características
- Modelado predictivo

## Resultados

El análisis de 112,328 vehículos eléctricos registrados en Washington State reveló que los BEV dominan el mercado con 76.4% frente al 23.6% de PHEV, con Tesla concentrando el 46.2% del total, Seattle como ciudad líder en adopción y 2022 como el año de mayor registro, confirmando una tendencia de crecimiento sostenida desde 2020. El modelo KNN con K=3 predijo el tipo de vehículo con un accuracy de 99.93% y F1-score de 99.91%, validado frente a un clasificador base de 76.43%, demostrando que electric_range es la variable más discriminante dado el mínimo solapamiento físico entre ambos tipos.

## Conclusiones

La concentración del 46.2% en Tesla indica una oportunidad de mercado real para otras marcas en el segmento BEV de largo alcance, donde existe demanda pero poca diversidad de oferta. Las ciudades del top 10, encabezadas por Seattle, deben priorizarse para inversión en infraestructura de carga rápida al ya contar con masa crítica de usuarios.



