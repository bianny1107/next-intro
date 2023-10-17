# next-intro

## ESLint 
<h5>
ESLint es una herramienta de análisis estático de código abierto que se utiliza para identificiar y corregir problemas en el código JavaScript, además de ayudar a mantener un estilo de código consistente, adherirse a las mejores prácticas de codificación y detectar problemas en una etapa temprana del proceso de desarrollo.

Las características de ESLint son:
- **Lintes (análisis)**: Escanea archivos de código JS para identificar el problema, además de violaciones de estilo de código, errores y patrones problemáticos. ESLint los informa como advertencias o errores (depende de la gravedad).

- **Configurabilidad**: El comportamiento de ESLint es ajustable mediante una configuración de reglas en un archivo de configuración que tiene por nombre _elintrc_. Es posible especificar las reglas habilitadas, modificar e incluso crear reglas personalizadas para hacer cumplir detalles específicos en el proyecto.

- **Plugins y configuraciones compartidas**: ESLint admite complementos y configuraciones compartidas. Los complementos amplían las capacidades de manejar diferentes marcos, a la vez que las configuraciones compartidas son conjuntos predefinidos de reglas y configuraciones para casos específicos.

- **Integración**: Es posible integrar en varios entornos de desarrollo y flujos de trabajo, como editores de código, sistemas de compilación y canalizaciones de CI/CD, de forma que sea posible proporcionar una retroalimentación en tiempo real y hacer cumplir estándares de calidad en el código.

- **Soporte de la comunidad**: La comunidad de ESLint es amplia y activa, permitiendo la existencia de una amplia gama de configuraciones y complementos.

Los desarrolladores suelen utilizar ESLint con otras aplicaciones, como _Prettier_ (para formatear código), con la finalidad de mantener una alta calidad y consistencia de código en los proyectos JavaScript.
</h5>

## Tailwind CSS
<h5>
Tailwind es un framework de diseño de CSS ampliamente utilizado dentro del área de desarrollo web, centrado en proporcionar utilidades de clase de bajo nivel que permiten a los desarrolladores construir interfaces web de manera más eficiente y personalizada.

Las características principales de Tailwind CSS son:
- **Utilidades de clase**: Proporciona un conjunto de clases predefinidas que se pueden aplicar directamente en el HTML para aplicar estilos a elementos específicos.
- **Configurabilidad**: Tailwind CSS tiene un alto nivel de configuración, permitiendo modificar paletas de colores o definir tamaños de texto.
- **Responsive design**: Incluye clases que permiten crear diseños responsivos de manera sencilla.
- **Modularidad**: El enfoque modular facilita la creación y el mantenimiento de estilos consistentes en grandes proyectos.
- **Extensibilidad**: Es posible extender Tailwind CSS con complementos y personalizaciones par agregar estilos o integrar funcionalidades adicionales.
- **Documentación amplia, además de ejemplos de uso que facilitan su aprendizaje e implementación**
</h5>

## Routing: Project organization and file colocation 
<h5>
En Next.JS, la organización y colocación de archivos es fundamentl para una gestión eficiente del proyecto. 
Algunas pautas para tener un proyecto organizado son:
- **Carpetas Pages de enrutamiento**: Utiliza las carpetas _pages_ para definir rutas web. Cada archivo dentro de la carpeta representará una ruta en el sitio.
- **Componentes reutilizables*: Se deben colocar dentro de la carpeta _components_ y organizarlos en subarpetas (dependiendo de su función).
- **Rutas dinámicas**: Es importante utilizar corchetes en los nombres de archivo en la carpeta _pages_ para crear rutas dinámicas.
- **API Routes**: Crear rutas de API en la carpeta _pages/API_.
- **Estilos y CSS**: Organizar los estilos en _styles_ o _public_.
- **Rutas anidadas**: Las rutas anidadas deben estar dentro de la carpeta _pages_.
- Configuración personalizada: Las reglas de enrutamiento y configuraciones adicionales deben ser definidas en el archivo _next.confi.js_.
- **Componentes páginas**: Los componentes de React y las páginas deben ser importadas desde los archivos en _pages_.
  **Enrutamiento dinámico**: Es posible aprovecharlo mejor mediante la creación de rutas basadas en datos en tiempo de ejecución.
</h5>
