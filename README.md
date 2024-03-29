# Basureroautomatico
![BA Encuentro Ingenia Futuro 2023-2S](https://github.com/Samitv77/Basureroautomatico/assets/146904463/2cf29491-a446-4da8-9da3-42c2f2ee5357)


# Resumen 
El proyecto propuesto para el desarrollo de un contenedor de residuos automático con tecnología ESP32 tiene un enfoque integral, abordando desafíos actuales en la gestión de residuos en lugares públicos. El alcance del proyecto se ha delineado cuidadosamente, incluyendo objetivos específicos, inclusiones, exclusiones, restricciones y un cronograma detallado.

El objetivo general de optimizar la recolección de residuos en áreas públicas, aumentando la eficiencia operativa y reduciendo la contaminación ambiental, se desglosa en objetivos específicos que abarcan desde el diseño del prototipo hasta la evaluación del rendimiento del sistema en entornos de prueba simulados.

La inclusión de tecnología ESP32, sensores ultrasónicos y un actuador (servomotor) es esencial para la detección precisa del nivel de llenado y la apertura controlada del contenedor. La programación a través de Thonny IDE con MicroPython asegura la interacción efectiva entre estos componentes.

El desarrollo de un algoritmo de control inteligente es clave para la automatización del proceso, permitiendo la apertura automática del contenedor cuando se detecta un nivel de llenado crítico. Esta característica contribuye a la optimización de la eficiencia de la recolección de residuos.

El alcance del proyecto incluye la validación del prototipo en entornos de prueba simulados para evaluar la efectividad y confiabilidad del sistema. Sin embargo, se excluye la producción a gran escala y la integración total en la infraestructura urbana existente, centrándose en la validación del concepto a nivel de prototipo.

Se establecen restricciones en términos de recursos técnicos y un límite presupuestario para garantizar una implementación económica y sostenible del proyecto.

El cronograma proporcionado guía el progreso del proyecto desde la fase de diseño hasta la evaluación y retroalimentación. Las fases de adquisición de materiales, desarrollo del código, integración de componentes, implementación del algoritmo y pruebas, validación en entornos de prueba, y documentación y presentación, están claramente definidas.

La última semana se reserva para la evaluación del prototipo y la recopilación de retroalimentación, permitiendo ajustes finales y mejoras basadas en los resultados obtenidos durante todo el desarrollo del proyecto.

El proyecto aborda de manera integral la gestión de residuos en entornos públicos, proponiendo una solución tecnológica innovadora que podría tener un impacto positivo en la eficiencia operativa y la reducción de la contaminación ambiental.


# Problematica
En entornos urbanos y lugares con mucha gente, la gestión de residuos es un desafío. La acumulación desigual de basura afecta la estética, la salud pública y el medio ambiente. La recogida manual tradicional es ineficiente y crea problemas. Esto lo podemos observar acá y en cualquier país Latinoamericano, por ende, es necesario hacer soluciones de forma que reduzcan este problema. Se Propone un contenedor automático con tecnología ESP32 que detecta y abre automáticamente según el nivel de llenado. Esto mejora la eficiencia al asignar recursos según la demanda real. La tecnología no solo optimiza la recolección de basura, sino que también reduce la contaminación ambiental al minimizar la exposición de residuos al aire libre.
Esta solución innovadora aborda los desafíos actuales de la gestión de residuos en lugares públicos, buscando una respuesta sostenible y tecnológica para mejorar la calidad ambiental en entornos urbanos con alta afluencia de personas.

# Alcance
En fase, el proyecto delinea claramente su alcance, enfocándose en la implementación de un basurero automatizado. El objetivo principal es proporcionar a los usuarios una experiencia única, caracterizada por la facilidad de uso y accesibilidad universal. La incorporación de elementos visuales, como LEDs, se contempla para mejorar la interacción del usuario con el basurero y garantizar una gestión eficiente de los residuos.

# Objetivos

Objetivo Especifico
•	Desarrollar e implementar un sistema automatizado de gestión de residuos mediante un contenedor de basura con tecnología ESP32 que optimice la recolección de residuos en áreas públicas, aumentando la eficiencia operativa y ayudando a reducir la contaminación ambiental.

Objetivos Generales

•	Diseñar y crear un prototipo de un bote de basura automático que pueda detectar con precisión su nivel de llenado mediante sensores integrados.
•	Programe el sistema utilizando Thonny IDE con MicroPython, asegurándose de que el ESP32, los sensores y el actuador (servomotor) interactúen correctamente.
•	Implemente un algoritmo de control que le permita abrir automáticamente el bote de basura cuando se detecte un nivel de llenado crítico, facilitando la recolección de residuos.

# Impactos 
![Captura de pantalla 2023-11-28 214726](https://github.com/Samitv77/Basureroautomatico/assets/146904463/488b4c39-565b-41b0-827d-e9040625fbca)

# Diseño: Caja Negra
![Captura de pantalla 2023-11-28 215027](https://github.com/Samitv77/Basureroautomatico/assets/146904463/3ee514d4-0979-47f0-aff6-02c30d3810f5)
[CAja_negra_diagrama (2).pdf](https://github.com/Samitv77/Basureroautomatico/files/13495587/CAja_negra_diagrama.2.pdf)

# Diseño Diagrama Tecnologico 
![Captura de pantalla 2023-11-28 220030](https://github.com/Samitv77/Basureroautomatico/assets/146904463/5a81fbe1-037c-4ab8-ad94-7109e5b8e338)
[Diagrama Tecnologico.pdf](https://github.com/Samitv77/Basureroautomatico/files/13495593/Diagrama.Tecnologico.pdf)

# Esquematico 
Cuaderno
![WhatsApp Image 2023-11-28 at 10 08 12 PM](https://github.com/Samitv77/Basureroautomatico/assets/146904463/916a5c5a-d875-4a84-8de7-be3ffd1aac4f)
![WhatsApp Image 2023-11-28 at 10 08 12 PM (1)](https://github.com/Samitv77/Basureroautomatico/assets/146904463/9a87a8ea-4cd0-44d7-b8e3-1dc5fabc238a)

Kicad
![Captura de pantalla 2023-11-28 221238](https://github.com/Samitv77/Basureroautomatico/assets/146904463/f7b52543-24a2-4876-90b1-c939434a768c)

# Esquematico PCB y PCB creada
Kicad

![Captura de pantalla 2023-11-28 221314](https://github.com/Samitv77/Basureroautomatico/assets/146904463/bc314822-979a-40ad-8f2e-4882df489571)

Impresa

![WhatsApp Image 2023-11-28 at 10 08 12 PM (2)](https://github.com/Samitv77/Basureroautomatico/assets/146904463/d0d00d23-b495-427d-b5df-12609003d19e)

Visor 3D

![Captura de pantalla 2023-11-28 222827](https://github.com/Samitv77/Basureroautomatico/assets/146904463/8b822c1e-45b7-4246-8405-b12b9e0c7e70)
![Captura de pantalla 2023-11-28 222856](https://github.com/Samitv77/Basureroautomatico/assets/146904463/a6ce9a61-640f-4d0c-aeaa-cb5e6de16066)


# Conclusiones

Este proyecto tiene varios puntos a favor:
1.	La introducción de un sistema automatizado de gestión de residuos: aborda directamente la problemática de la acumulación descontrolada. Al incorporar el sensor ultrasónico y el servomotor, se logra una recolección más precisa y oportuna, evitando desbordamientos y ayudando a la preservación del entorno.

2.	La elección del ESP32 como plataforma central: destaca la importancia de la versatilidad y programabilidad en la implementación de soluciones tecnológicas. Esta elección no solo facilita la interacción sin problemas entre los componentes del sistema, sino que también permite adaptarse a futuras mejoras y actualizaciones.

3.	Su funcionalidad técnica: este cubo de basura automático se integra perfectamente en la visión de entornos urbanos más limpios y sostenibles. La combinación de tecnología y conciencia ambiental refuerza la idea de que la innovación puede desempeñar un papel clave en la transformación positiva de nuestras comunidades.

El proyecto no solo  propone una solución eficiente para el manejo de residuos en espacios públicos, sino que también se presenta como una idea útil de cómo la tecnología, cuando se aplica de manera inteligente, puede contribuir significativamente a la construcción de un futuro más sostenible y saludable.



