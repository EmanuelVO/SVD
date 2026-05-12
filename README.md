# SVD

1. Considera nuevamente la base de datos de estudiantes siguiente: Actividad Introducción a la descomposición de valores singulares (SVD).

<img width="309" height="194" alt="image" src="https://github.com/user-attachments/assets/ae5b087c-91e2-4ff7-b8b0-c45cffd580c0" />


2. Aplica el algoritmo SVD para separar por grupos mediante reducciones a dos y tres dimensiones.

<img width="498" height="384" alt="image" src="https://github.com/user-attachments/assets/41c38d2d-a65b-4049-9595-205156804303" />

<img width="371" height="351" alt="image" src="https://github.com/user-attachments/assets/7da09c6b-a352-41a3-a947-296f5ff50d51" />

<img width="747" height="515" alt="image" src="https://github.com/user-attachments/assets/babfecac-5036-4592-b8a7-ebc94b74ce63" />

<img width="750" height="518" alt="image" src="https://github.com/user-attachments/assets/b23f968f-3be5-4984-be6a-5c1450e9afa6" />


3. ¿Cuál de las separaciones previas es más clara?

En 2D ya se conserva la mayor parte de la información. En 3D mejora la precisión de la representación, pero no siempre mejora la visualización si los grupos ya están bien separados en 2D. En 2D, normalmente puedes ver dos o tres agrupamientos claros de estudiantes con calificaciones similares. En 3D, aunque la representación es más fiel, la visualización depende del ángulo y es más difícil interpretar sin rotar el gráfico. En conclusión, La separación más clara visualmente suele ser la de 2 dimensiones, porque permite observar los grupos de estudiantes de manera directa y comprensible, manteniendo una alta proporción de la varianza. Sin embargo, si se busca mayor precisión analítica la versión 3D es la mejor, ya que retiene más información del conjunto original. 

¿Difieren sus resultados de aquellos obtenidos previamente mediante el análisis de componentes principales?

Los valores de varianza explicada son casi iguales, lo que confirma que en este dataset (centrado naturalmente y con escalas similares), SVD y PCA producen resultados muy parecidos. En los gráficos podemos notar que la disposición de los alumnos es muy similar, con ligeras diferencias de rotación o escala. 
