# Ctrl Gastos

Ctrl Gastos es una aplicación de ejemplo para aprender los fundamentos de Flutter mientras se construye algo práctico: una app sencilla para organizar ingresos y gastos.

Este proyecto lo desarrollo con un propósito educativo, especialmente para jóvenes que están dando sus primeros pasos en el desarrollo de aplicaciones. La idea es aprender viendo y modificando código real, avanzar poco a poco y descubrir cómo las distintas partes de una app trabajan juntas.

> **Proyecto de aprendizaje:** algunas pantallas usan información de demostración y la aplicación no está pensada para gestionar finanzas reales.

## ¿Qué puedes explorar?

- Pantalla de inicio de sesión y formulario de registro.
- Panel con saldo, ingresos, gastos y actividad reciente.
- Formularios, validación de campos y controladores de texto.
- Navegación entre pantallas con rutas nombradas.
- Widgets reutilizables y temas claro y oscuro.
- Organización del código en capas de presentación, dominio y datos.
- Persistencia local con SQLite usando `sqflite`.
- Carga asíncrona de información y estados de espera y error.

## ¿Qué puedes aprender?

Al explorar o extender Ctrl Gastos podrás practicar:

1. Cómo se inicia una aplicación Flutter y cómo se construyen interfaces con widgets.
2. Cómo responder a interacciones usando estado y `setState`.
3. Cómo crear formularios y validar los datos ingresados.
4. Cómo separar pantallas, modelos, repositorios y acceso a datos.
5. Cómo guardar y consultar información localmente.
6. Cómo mostrar datos asíncronos en la interfaz.

No necesitas entender todo de una vez: puedes empezar siguiendo el flujo de una pantalla y luego probar pequeños cambios.

## Requisitos

- Flutter SDK instalado y configurado.
- Un emulador, simulador o dispositivo compatible, o un destino de escritorio/web habilitado en Flutter.

## Ejecutar el proyecto

Clona el repositorio y entra en la carpeta:

```bash
git clone https://github.com/edd86/ctrl_gastos.git
cd ctrl_gastos
```

Instala las dependencias y ejecuta la aplicación:

```bash
flutter pub get
flutter run
```

## Estructura del proyecto

```text
lib/
├── core/       # Base de datos, rutas, tema y widgets compartidos
└── features/   # Funcionalidades de autenticación, inicio, usuarios y transacciones
```

Cada funcionalidad se organiza, cuando corresponde, en capas de presentación, dominio y datos. Es una oportunidad para conocer una forma de mantener el código más ordenado a medida que la aplicación crece.

## Ideal para aprender haciendo

Puedes usar Ctrl Gastos como punto de partida para experimentar: cambia textos y colores, agrega campos, crea una pantalla nueva o intenta guardar otro tipo de dato. Si estás aprendiendo Flutter con otras personas, este proyecto también puede servir como base para explicar cada concepto paso a paso.
