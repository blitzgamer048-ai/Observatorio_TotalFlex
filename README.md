# Observatorio de Total Flex
Gimnasios del centro de Loja. Proyecto integrador de Programación Aplicada a la
Inteligencia de Mercados (UIDE Loja).
## Pregunta de negocio
¿Debemos subir los precios de las mensualidades para aumentar los ingresos sin
perder clientes?
## Quién decide y qué decisión apoya
- **Quién decide:** Gerente del gimnasio
- **Decisión:** Definir los precios de las mensualidades y las promociones según la
competencia y la demanda
## Indicadores
- Precio de las mensualidades de los gimnasios competidores
- Número de promociones y descuentos ofrecidos por la competencia
## Fuentes previstas
- Redes sociales y páginas web oficiales de los gimnasios
- Google Maps y publicaciones publicitarias de los competidores
## Estructura del proyecto
- `data/raw/`: datos originales (no se modifican)
- `data/processed/`: datos limpios
- `notebooks/`: cuadernos de análisis
- `src/`: funciones reutilizables
- `reports/`: resultados para quien decide
- `pyproject.toml`: dependencias del proyecto
## Cómo ejecutar
Abrir el cuaderno en Google Colab y usar *Entorno de ejecución > Reiniciar sesión y
ejecutar todo*.
## Declaración de uso de IA
Usé ChatGPT para organizar y redactar la propuesta.

## Supuesto 1: Los gimnasios del centro de Loja que ofrecen mensualidades más económicas atraen a más clientes que aquellos con precios elevados.

##  Supuesto 2: Las promociones y descuentos de los gimnasios competidores influyen en la decisión de los clientes de inscribirse o renovar sus mensualidades.

## Limitación: La información sobre precios y promociones publicada en redes sociales puede estar desactualizada. Además, no tenemos acceso a la cantidad real de clientes de los gimnasios competidores.

## ¿Por qué importa para el decisor?
Esta información permitirá al gerente de Total Flex comparar sus precios con los de la competencia y decidir si es conveniente aumentar las mensualidades o implementar promociones para incrementar los ingresos sin perder clientes.
