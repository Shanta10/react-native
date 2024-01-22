**¿Qué problemas específicos de rendimiento o mantenibilidad se identificaron en la aplicación original?**

En la aplicación original, el ancho del botón primario (Choose a photo) en Button.js no estaba controlado y podría haber afectado la presentación visual de la interfaz de usuario. Además, el estilo del botón primario no estaba claramente diferenciado, lo que podría haber dificultado futuras modificaciones.

La modificación en Button.js permite que el ancho del botón primario sea más configurable y controlado desde el lugar donde se utiliza el componente, en lugar de estar fijado en el propio componente. Esto sigue el principio de diseño de componentes más flexibles y fácilmente adaptables.

**¿Cómo se aseguró que el refactoring no afectara negativamente la funcionalidad existente?**

El refactoring se enfocó en mejorar la claridad del código y controlar el ancho del botón primario. Se aseguró de mantener la funcionalidad existente probando la aplicación después del cambio y verificando visualmente que el diseño y la interactividad permanecieran sin cambios.

**¿Qué mejoras de rendimiento y mantenibilidad se lograron con el refactoring?**

El refactoring mejoró la mantenibilidad al organizar y diferenciar claramente los estilos de los botones en Button.js. Además, se controló el ancho del botón primario para evitar valores excesivos, lo que podría haber afectado negativamente la presentación visual.

**¿Cuáles fueron los desafíos más significativos durante el proceso de refactoring y cómo se superaron?**

Un desafío fue asegurarse de que el cambio en el ancho del botón primario no afectara otras partes de la interfaz de usuario. Se superó ajustando el valor del ancho y probando la aplicación visualmente para garantizar que el cambio fuera aceptable.

**¿Qué impacto tuvo el refactoring en la experiencia del usuario final?**

El impacto en la experiencia del usuario final es positivo en términos de claridad del código y presentación visual mejorada del botón primario.

**¿Cómo se podrían aplicar las lecciones aprendidas en este proyecto a futuros proyectos de desarrollo y refactoring?**

Las lecciones aprendidas incluyen la importancia de organizar y diferenciar claramente los estilos en componentes reutilizables, así como controlar cuidadosamente los valores visuales para mantener una interfaz de usuario coherente. Estas prácticas pueden aplicarse en futuros proyectos para mejorar la mantenibilidad y la calidad del código.

