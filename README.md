# PuntoVentaCloud

Sistema Integral de Gestión para Pequeños Comercios.

PuntoVentaCloud es un sistema diseñado para optimizar la operatividad de pequeños comercios. La solución integra una aplicación de escritorio TPV, una API REST alojada en un servidor, una base de datos MySQL y una aplicación móvil para Android.

Este sistema permite:

    Procesar ventas y gestionar inventario.
    Consultar información clave en tiempo real.
    Garantizar la seguridad y disponibilidad de los datos en la nube.

Tecnologías Utilizadas

    C# / WPF: Aplicación de escritorio TPV.
    .NET Core: API RESTful para la integración de datos.
    MySQL: Base de datos relacional alojada en un VPS.
    Kotlin: Aplicación móvil Android.

Estructura del Proyecto

Este repositorio central enlaza a los componentes individuales:
1. Aplicación de Escritorio (TPV)

    Descripción: Sistema TPV desarrollado en C# utilizando WPF.
    Características:
        Gestión de ventas e inventario.
        Funcionalidades específicas para hostelería (asignación de mesas).
        Generación de informes de ventas y caja.
    Repositorio: TPV Escritorio - GitHub

2. API RESTful

    Descripción: API desarrollada en .NET Core 8.0.
    Características:
        Sincronización en tiempo real con la base de datos.
        Acceso seguro mediante autenticación JWT.
        Documentación con Swagger.
    Repositorio: API RESTful - GitHub

3. Base de Datos

    Descripción: Base de datos alojada en un servidor VPS con MySQL.
    Características:
        Gestión eficiente de grandes volúmenes de datos.
        Seguridad avanzada con restricciones de acceso.
    Repositorio: (Los scripts y configuración detallada se encuentran en el repositorio de la API).

4. Aplicación Móvil (Android)

    Descripción: Aplicación desarrollada en Kotlin con arquitectura MVVM.
    Características:
        Consulta remota de datos clave: ventas, cierres de caja y accesos.
        Interfaz moderna usando Jetpack Compose.
    Repositorio: Aplicación Móvil Android - GitHub
