# Modelo multidimensional y cubo de Ventas (SSAS)

Proyecto académico desarrollado en la Especialización en Inteligencia de Negocios y Analítica de Datos (Cibertec). Es un ejercicio guiado sobre el datamart Northwind_Mart, provisto por el curso.

## Qué contiene
- **Origen y vista de datos:** conexión a Northwind_Mart y una vista con 8 tablas.
- **Cálculos con nombre:** NombreClienteCod, Trimestre, Semestre y Mes.
- **7 dimensiones:** Cliente, Empleado, Transporte, Producto, Tiempo, Proveedor y Ordenes.
  - Jerarquías de ubicación, categoría y calendario.
  - Relaciones entre atributos.
  - Discretización por áreas iguales (4 grupos) sobre el precio unitario.
  - Nombre del miembro "All" personalizado.
- **Cubo Ventas:** medidas de ventas, relación referenciada (Proveedor vía Producto) y dimensión degenerada (Ordenes).

## Herramientas
SQL Server 2022 · SQL Server Analysis Services (modelo multidimensional) · Visual Studio · MDX

## Cómo reproducirlo
1. Restaurar la base `Northwind_Mart` en SQL Server.
2. Abrir la solución en Visual Studio.
3. Ajustar la cadena de conexión del origen de datos.
4. Desplegar y procesar el cubo.

## Capturas
Ver la carpeta `/capturas` (dimensiones, cubo y resultados de las consultas).

## Consultas MDX
Ver la carpeta `/mdx`: ventas por año, ventas por trimestre, top 10 de clientes y ventas por categoría de producto.

## Nota
El diseño del ejercicio y la base de datos pertenecen al curso. El trabajo propio es el desarrollo del modelo y del cubo.
