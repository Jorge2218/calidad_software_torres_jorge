# Calidad de Software

Repositorio de apoyo para la materia de Calidad de Software. Este documento presenta conceptos básicos para comprender la importancia de la calidad en el desarrollo de software y cómo las pruebas ayudan a asegurar que una aplicación funcione de manera confiable.

## Objetivo

La calidad de software se refiere a la capacidad de un sistema para cumplir con los requisitos, satisfacer las necesidades del usuario y mantener un nivel aceptable de confiabilidad, mantenibilidad, seguridad y rendimiento.

## Conceptos básicos

### 1. Requisitos
Los requisitos describen qué debe hacer el software y bajo qué condiciones. Pueden ser:

- Funcionales: comportamiento esperado del sistema.
- No funcionales: rendimiento, seguridad, usabilidad, escalabilidad y mantenibilidad.

### 2. Calidad de software
Un software de calidad debe ser:

- Correcto: cumple con lo que se requiere.
- Confiable: se comporta de forma estable.
- Mantenible: fácil de modificar y extender.
- Seguro: protege datos e integridad del sistema.
- Eficiente: usa recursos de forma adecuada.

### 3. Pruebas de software
Las pruebas permiten detectar errores antes de que el sistema llegue al usuario final. Son esenciales para mejorar la confianza y reducir riesgos.

## Pruebas unitarias

Las pruebas unitarias validan unidades pequeñas del código, como funciones, métodos o clases, de manera aislada.

### Características principales
- Se enfocan en un solo comportamiento.
- Son rápidas de ejecutar.
- Ayudan a detectar errores en lógica específica.
- Se usan frecuentemente durante el desarrollo.

### Ejemplo de objetivo
Verificar que una función de suma retorne el resultado correcto para diferentes entradas.

### Buenas prácticas
- Mantenerlas pequeñas y claras.
- Probar casos normales y casos límite.
- Evitar dependencias complejas entre pruebas.
- Ejecutarlas con frecuencia en el proceso de desarrollo.

## Pruebas E2E (End-to-End)

Las pruebas E2E validan el flujo completo de una aplicación desde la perspectiva del usuario. Simulan interacciones reales con la interfaz o el sistema para comprobar que el comportamiento global es correcto.

### Características principales
- Reproducción de flujos reales de uso.
- Validan integración entre componentes.
- Detectan fallos que pueden no verse en pruebas unitarias.
- Son más lentas que las pruebas unitarias, pero aportan mayor confianza.

### Ejemplo de objetivo
Verificar que un usuario puede iniciar sesión, navegar a una sección y completar una acción importante.

## Relación entre pruebas unitarias y E2E

Ambas son importantes y complementarias:

- Las pruebas unitarias detectan fallos puntuales y rápidos.
- Las pruebas E2E verifican la experiencia del usuario y la integración del sistema.

Una estrategia sólida suele combinar ambas para obtener mayor cobertura y confianza.

## Recomendaciones para un proyecto

- Definir requisitos claros antes de desarrollar.
- Escribir pruebas desde el inicio.
- Usar pruebas unitarias para lógica crítica.
- Añadir pruebas E2E para flujos importantes del negocio.
- Revisar y mantener la calidad del código con regularidad.

## Conclusión

La calidad de software no es un detalle opcional, sino una parte esencial del desarrollo profesional. Las pruebas unitarias y las pruebas E2E son herramientas clave para garantizar que el software sea funcional, confiable y útil para los usuarios.
