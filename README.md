# Resumen ejecutivo de ventas Walmart: eficiencia y participación por departamento

## Desafío
La Dirección Comercial de Walmart necesitaba un resumen ejecutivo para decidir 
ajustes de presupuesto e inventario, respondiendo dos preguntas: qué departamentos 
fueron más eficientes generando ventas por metro cuadrado en 2012, y cuáles 
aportaron más al negocio frente a los que estuvieron por debajo de su potencial.

En resumen, este proyecto es descubrir qué departamentos de Walmart aprovechan 
mejor su espacio en tienda y cuáles no, para saber dónde vale la pena invertir más 
metros y dónde conviene reducir.

## Datos
Datos de ventas semanales de 2012 por tienda y departamento, junto con catálogos de 
departamentos (nombres) y tiendas (tipo A/B y tamaño en m²), todo trabajado en 
Excel/Google Sheets.

## Proceso
- Limpieza de los datos crudos: unión de ventas con los catálogos de departamento y 
  tienda, estandarización de fechas y descarte de registros inconsistentes (tiendas 
  sin departamento asignado)
- Validaciones de calidad de datos (QA): verificación de tiendas sin departamento, 
  ventas negativas o nulas, y tamaños en m² en cero, cada una documentada con su 
  fórmula y resultado
- Construcción de dos KPIs mediante tablas dinámicas: ventas por metro cuadrado 
  (eficiencia) y participación de cada departamento en las ventas totales
- Creación de un dashboard interactivo con menú desplegable por departamento, 
  gráficos y resaltado de valores por debajo de los umbrales clave ($200.000 y 5%)
- Resumen ejecutivo con el método Contexto → Hallazgo → Implicación, respondiendo 
  directamente las dos preguntas de negocio

Nunca había construido un dashboard dentro de Excel, siendo más cercano a Power BI 
para ese tipo de trabajo, así que ese fue el reto principal del proyecto. También 
fue la primera vez armando tablas dinámicas pensando bien en qué campo va en cada 
lugar (filas, columnas, valores) para extraer justo la información que se 
necesitaba. Aprender a construir esa lógica sin depender de Power BI fue lo que más 
me llevé de este proyecto.

## Resultado
- "Cuidado del bebé y la familia" fue el departamento más eficiente en ventas por 
  m², con $591, seguido de "Oficina, escuela y mantenimiento" con $342
- "Automotriz", "Artículos del hogar y papel" y "Ropa" tienen los niveles más bajos 
  de eficiencia, por debajo de $200 por m²
- "Cuidado del bebé y la familia" también tiene la mayor participación en ventas 
  totales (13.15%), seguido de "Salud y Bienestar" (11.44%) y "Comida Fresca" 
  (10.05%)
- "Artículos del Hogar y Papel", "Ropa", "Hogar y Temporada", "Juguetes y Juegos" y 
  "Electrónica de Consumo" tienen una participación menor al 5%

## Recomendaciones / Siguientes pasos
1. Asignar más metros cuadrados a "Cuidado del bebé y la familia", dada su alta 
   eficiencia en el espacio que ya tiene.
2. Optimizar o reducir el espacio de los departamentos con eficiencia por debajo de 
   $200 por m², ya que no están aprovechando bien el espacio asignado.
3. Para los departamentos con baja eficiencia y baja participación a la vez, 
   reducir su espacio y buscar estrategias para aumentar sus ventas; para los que 
   tienen alta eficiencia pero baja participación, mantener o ampliar su espacio y 
   buscar estrategias que aumenten su participación en ventas.

## Visuales
<img width="1142" height="526" alt="Resumen Ejecutivo" src="https://github.com/user-attachments/assets/9fec2e0a-7680-458f-949b-80a63f86b2d3" />
<img width="1346" height="717" alt="Dashboard" src="https://github.com/user-attachments/assets/27ae91c7-ca2f-4e4a-8ee0-2fa371c99ba4" />

## Entregable
Archivo de Excel con todas las hojas del proceso (datos crudos, datos limpios, 
tablas dinámicas, dashboard y resumen ejecutivo): https://drive.google.com/drive/folders/1_FXcqfcaNWCn2Sq8bSUeZBgalisIgXW4?usp=sharing
