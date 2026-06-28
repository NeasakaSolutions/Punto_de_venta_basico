# Punto de Venta para Restaurante

## Descripción

Sistema de Punto de Venta (POS) para un restaurante, desarrollado como una solución sencilla para administrar las operaciones básicas del negocio.

La primera versión estará enfocada en cubrir las necesidades esenciales del restaurante mediante un único usuario con rol de **Administrador**, quien tendrá acceso a todas las funcionalidades del sistema.

El proyecto será diseñado con una arquitectura modular para facilitar la incorporación de nuevas características en futuras versiones.

---

# Objetivos

* Administrar productos del restaurante.
* Controlar el inventario.
* Gestionar pedidos por mesa.
* Calcular automáticamente el total de cada cuenta.
* Registrar ventas.
* Generar reportes básicos de ingresos y ganancias.
* Automatizar el cierre diario de caja.

---

# Alcance (MVP)

## Seguridad

* Inicio de sesión.
* Un único usuario con rol de **Administrador**.

---

## Gestión de Productos

* Crear productos.
* Editar productos.
* Eliminar productos.
* Consultar listado de productos.

Cada producto contará con información básica:

* Nombre
* Precio de venta
* Costo
* Categoría
* Existencia en inventario

---

## Inventario

* Registro de existencias.
* Actualización automática del inventario al entregar un producto.
* Modificación manual de existencias por parte del administrador.
* Consulta del inventario actual.

---

## Gestión de Mesas

* Crear pedido por mesa.
* Agregar productos al pedido.
* Modificar cantidades.
* Eliminar productos del pedido.
* Visualizar el estado de las mesas.

Estados:

* Libre
* Ocupada

---

## Ventas

* Calcular automáticamente el total de la cuenta.
* Registrar el pago.
* Marcar la mesa como disponible al finalizar la venta.

---

## Caja

* Registro de ventas del día.
* Cierre automático de caja por fecha.
* Consulta del historial de cierres.

---

## Reportes

* Ventas del día.
* Ventas por rango de fechas.
* Ganancias netas.
* Productos más vendidos.
* Estado del inventario.

---

# Requisitos No Funcionales

* Interfaz simple e intuitiva.
* Operaciones rápidas.
* Base de datos relacional.
* Código organizado para facilitar mantenimiento.
* Arquitectura preparada para futuras funcionalidades.

---

# Funcionalidades Futuras

Estas características no forman parte de la primera versión, pero la arquitectura deberá permitir incorporarlas posteriormente:

* Múltiples usuarios.
* Roles (Administrador, Cajero, Mesero).
* División de cuentas.
* Descuentos.
* Propinas.
* Reservaciones.
* Impresión de tickets.
* Facturación.
* Dashboard con estadísticas.
* Control de cocina.
* Integración con terminales de pago.

---

# Flujo General del Sistema

1. El administrador inicia sesión.
2. Administra los productos e inventario.
3. Se crea un pedido para una mesa.
4. Se agregan productos al pedido.
5. El sistema calcula automáticamente el total.
6. Se registra el pago.
7. El inventario se actualiza automáticamente.
8. La mesa queda disponible nuevamente.
9. La venta queda registrada para los reportes y el cierre de caja.

---

# Objetivo de Desarrollo

Construir un sistema sencillo, funcional y escalable que sirva como base para futuras versiones con nuevas funcionalidades, manteniendo una estructura de código limpia y modular.

