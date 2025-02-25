# proyecto_comportamiento_usuario
## Análisis de comportamiento de usuarios y embudo de ventas
El objetivo de este proyecto es analizar y comprender el comportamiento de los usuarios dentro de la aplicación. A través de esta investigación, buscamos identificar patrones de uso, preferencias y comprobar una hipotesis (experimento A/A/B) para ver si el diseño de la pagina afecta el comportamiento de los clientes **Mejorar la conversión**

#### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Plotly-%23357ebd.svg?style=for-the-badge&logo=matplotlib&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Tests A/B](https://img.shields.io/badge/Tests_A/B-295F98?style=for-the-badge)
![Pruebas de hipótesis](https://img.shields.io/badge/Pruebas_de_hipótesis-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)
![Scipy](https://img.shields.io/badge/scipy-295F98?style=for-the-badge)
![Math](https://img.shields.io/badge/math-295F98?style=for-the-badge)

### Preguntas clave
1. ¿Qué eventos del embudo de ventas tienen mayores tasas de abandono? ¿Que etapas en particular?
2. ¿Qué porcentaje de usuarios completa el embudo de ventas desde el inicio hasta el pago?
3. ¿El cambio en el diseño de las fuentes afecta significativamente la conversión?
4. ¿Hay diferencias estadísticas entre los grupos de control y el grupo de prueba?

### Metodología
- **Preprocesamiento de datos:** Se ajustaron los nombres de las columnas, se eliminaron duplicados y se filtraron registros incompletos.
- **Estudiar y comprobar los datos:** Se identica el numero de etapas, promedio de etapas por usuario.
- **Análisis del embudo de ventas:** Se identificaron eventos clave y la proporción de usuarios que avanzan entre etapas, como tambien cuales son las etapas con mayor tasa de abandono y el porcentaje de usuarios que hacen todo el viaje desde su primer evento hasta la compra.
- **Experimentación A/A/B:** Se compararon conversiones entre grupos de control y prueba mediante pruebas de hipótesis estadísticas.

### Conclusiones

#### Embudo de ventas:
- Se trabajo solo con datos de una semana debido a que el 99% de la información se encontraba alli.
- El evento OffersScreenAppear es donde más usuarios abandonan (61.9%).
- Solo el 47.7% de los usuarios completa el embudo de ventas hasta el pago exitoso.
- No todos los usuarios siguen la ruta predestinada

#### Resultados del experimento:
- No se encontraron diferencias estadísticas significativas entre los grupos de control y el grupo de prueba.
- Las nuevas fuentes no generan un impacto positivo en la conversión, por lo que no se recomienda implementar este cambio.

#### Recomendaciones: 
 Optimizar la pantalla de ofertas y pago exitoso para retener más usuarios en esa etapa.
- Priorizar otros cambios en el diseño o funcionalidad de la aplicación con mayor potencial de impacto.

### Visualizaciones destacadas
1. **Periodo de tiempo de los datos:** Se Pudo visualizar que la mayoria de datos se concentra en las fechas del 1 al 7 de agosto. 241298 (mas del 99%) filas pertenecen al mes de agosto y 2828 filas al mes de julio. Por lo que trabajaremos con los datos del solo el mes de agosto ya que los demas datos podrian sesgar el panorama. Ya con esta información con los datos que trabajaremos solo cubre Una semana
![Periodo de tiempo de los datos](https://imgur.com/a/G2Ojzy0)
