# Descripción Mejorada

Este proyecto, implementado en Angular e Ionic, consiste en una aplicación móvil enfocada en la gestión de ahorros personales a través de la utilización de "cofres". El usuario puede personalizar cada cofre asignándole un nombre, una prioridad, un monto objetivo de ahorro y una fecha límite. La pantalla principal muestra los cofres existentes, que representan las distintas metas financieras del usuario. Al acceder a un cofre, según su tipo, se presenta información relevante como el total acumulado, cuánto se debería ahorrar o depositar, ajustándose al método de ahorro seleccionado.

## Tecnologías Empleadas

- Angular v16
- Ionic v7
- Dependencias:
  - `@angular/animations: ^16.0.0`
  - `@angular/forms: ^16.0.0`
  - `@angular/router: ^16.0.0`
  - `@capacitor-community/admob: ^5.0.0`
  - `@capacitor/android: 5.5.1`
  - `@capacitor/app: 5.0.6`
  - `@ionic/angular: ^7.0.0`
  - `animate.css: ^4.1.1`
  - `ionicons: ^7.0.0`
  - `rxjs: ~7.8.0`
  - `@ngx-translate/core: 15`
- Tailwind CSS

## Características Principales

La aplicación almacena todos los datos mediante localStorage. CoinCoffer ofrece tres modalidades de ahorro:

- **Ahorro fijo:** Permite establecer un objetivo de ahorro con una fecha y monto específico.
- **Ahorro libre:** Facilita el registro de depósitos sin una meta predeterminada.
- **Reto de ahorro:** Programa un monto específico para ahorrar de forma diaria, semanal o mensual, cumpliendo la meta en la fecha establecida.

## Lenguajes Disponibles

- Español
- Inglés

## Utilidades de Angular Aplicadas

- Servicios
- Pipes
- Interfaces
- Rutas
- Formularios Reactivos

## Diagrama de Estructura de Módulos y Componentes

 <p align="center">
 <img src="/img_readme/diagrama1.png" width="500">
</p>

 <p align="center">
 <img src="/img_readme/diagrama2" width="500">
</p>

- **AppModule:** Este es típicamente el módulo raíz que inicia y lanza la aplicación Angular.
- **AppRoutingModule:** Gestiona el enrutamiento de la aplicación, definiendo rutas a los distintos componentes.
- **AppComponent:** El componente raíz que actúa como contenedor de la aplicación.
- **ChestsPageModule:** Módulo de visión general de los cofres.
- **Varios Componentes:** PopupNotaComponent, ModalEditComponent, ModalConfigComponent, HistorialModalComponent, HeaderComponent, ErrorMessageComponent y CalendarComponent son componentes que se usan en diferentes partes de la aplicación para varios elementos de la interfaz de usuario como modales, encabezados, mensajes de error y calendarios.
- **ChallengeChestPageModule:** Módulo dedicado a la creación de cofre de ahorro de tipo "Reto de cofre".
- **LimitedChestPageModule:** Módulo para la creación de cofres de ahorro con meta fija.
- **UnlimitedChestPageModule:** Módulo para la creación de cofres de ahorros de tipo "sin límite".
- **NewChestPageModule:** Este módulo estructura el tipo de cofre de ahorro a crear.
- **OpenChestPageModule:** Este módulo maneja la funcionalidad para ver el contenido o el estado de un cofre abierto.
- **StartChestPageModule:** Corresponde al proceso para iniciar o empezar un nuevo cofre de ahorros.
- **TranslateNoIdPipe, TranslateDepositPipe:** Estos son Pipes de Angular para transformar texto, relacionados con la internacionalización o el formateo de la información de depósitos.

## Sistema de Rutas

 <p align="center">
 <img src="/img_readme/rutas.png" width="500">
</p>
