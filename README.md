# Proyecto-de-Analisis-de-Negocio-----Y.Afisha
Realizar un analisis de datos para toma de decisiones y ayudar a optimizar los gastos de marketing.

Lo que tienes: registros del servidor con datos sobre las visitas a Y.Afisha desde enero de 2017 hasta diciembre de 2018;
un archivo con los pedidos en este periodo; estadísticas de gastos de marketing.

Lo que vas a investigar:

cómo los clientes usan el servicio;
cuándo empiezan a comprar;
cuánto dinero aporta cada cliente a la compañía;
cuándo los ingresos cubren el costo de adquisición de los clientes.

Instrucciones para completar el proyecto

-- Paso 1. Descarga los datos y prepáralos para el análisis
Almacena los datos de visitas, pedidos y gastos en variables.  Optimiza los datos para el análisis. Asegúrate de que cada columna contenga el tipo de datos correcto.

Rutas de archivos: 

/datasets/visits_log_us.csv.
/datasets/orders_log_us.csv.
/datasets/costs_us.csv.

-- Paso 2. Haz informes y calcula métricas 

Visitas:
¿Cuántas personas lo usan cada día, semana y mes?
¿Cuántas sesiones hay por día? (Un/a usuario/a puede tener más de una sesión).
¿Cuál es la duración de cada sesión?
¿Con qué frecuencia los usuarios y las usuarias regresan?

Ventas:
 ¿Cuándo la gente empieza a comprar? (En el análisis de KPI, generalmente nos interesa saber el tiempo que transcurre entre el registro y la conversión, es decir, cuando el/la usuario/a se convierte en cliente. Por ejemplo, si el registro y la primera compra ocurren el mismo día, el/la usuario/a podría caer en la categoría Conversion 0d. Si la primera compra ocurre al día siguiente, será Conversion 1d.  Puedes usar cualquier enfoque que te permita comparar las conversiones de diferentes cohortes para que puedas determinar qué cohorte o canal de marketing es más efectivo).
¿Cuántos pedidos hacen durante un período de tiempo dado?
¿Cuál es el tamaño promedio de compra?
¿Cuánto dinero traen? (LTV)

Marketing:
¿Cuánto dinero se gastó? (Total/por fuente de adquisición/a lo largo del tiempo)
¿Cuál fue el costo de adquisición de clientes de cada una de las fuentes?
¿Cuán rentables eran las inversiones? (ROMI)

Traza gráficos para mostrar cómo difieren estas métricas para varios dispositivos y fuentes de anuncios y cómo cambian con el tiempo. 

-- Paso 3. Escribe una conclusión: aconseja a los expertos de marketing cuánto dinero invertir y dónde

¿Qué fuentes/plataformas recomendarías?  Fundamenta tu selección: ¿en qué métricas te enfocaste?  ¿Por qué? ¿Qué conclusiones sacaste después de encontrar los valores métricos?

Formato: Completa la tarea en un Jupyter Notebook. Inserta el código en las celdas code y las explicaciones de texto en las celdas markdown. Aplica formato y encabezados.

-- Descripción de los datos
La tabla visits (registros del servidor con datos sobre las visitas al sitio web):
Uid: identificador único del usuario;
Device: dispositivo del usuario;
Start Ts: fecha y hora de inicio de la sesión;
End Ts: fecha y hora de término de la sesión;
Source Id: identificador de la fuente de anuncios de la que proviene el usuario.
Todas las fechas de esta tabla están en formato AAAA-MM-DD.

-- La tabla orders (datos sobre pedidos):
Uid: identificador único del usuario que realiza un pedido;
Buy Ts: fecha y hora del pedido;
Revenue: ingresos de Y.Afisha de este pedido.

-- La tabla costs (datos sobre gastos de marketing):
source_id: identificador de la fuente de anuncios
dt: fecha;
costs: gastos en esta fuente de anuncios en este día.

Esto es lo que buscan los revisores de proyecto cuando evalúan tu proyecto:

cómo preparas los datos para el análisis;
qué gráficos trazas para las métricas;
cómo interpretas los gráficos resultantes;
cómo calculas e interpretas cada parámetro;
cómo fundamentas tus recomendaciones para los expertos de marketing y qué métricas utilizas;
si sigues la estructura del proyecto y mantienes el código ordenado;
las conclusiones a las que llegas;
si dejas comentarios en cada paso.
