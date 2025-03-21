El Reino del Vacío
Lista de Características
1)	Género: Roguelike de cartas por turnos en 2D, estilo pixel art.
a.	El jugador deberá crear y mejorar su mazo de cartas para enfrentarse a enemigos en batallas tácticas.
b.	Inspirado en juegos como Slay the Spire y Monster Train, pero con un enfoque narrativo más profundo.
2)	Estructura del juego:
a.	Niveles divididos en diferentes encuentros: batallas, eventos aleatorios y tiendas.
b.	Cada nivel presenta desafíos crecientes y enemigos con mecánicas variadas.
c.	La progresión del jugador está basada en la adquisición y mejora de cartas.
3)	Mecánicas clave:
a.	Sistema de combate por turnos con gestión estratégica de recursos (maná, vida y efectos de estado).
b.	Cartas con efectos variados como ataques, defensa, mejoras temporales y habilidades especiales.
c.	Eventos con elecciones que pueden modificar el curso del juego.
4)	Interfaz:
a.	Estilo oscuro y medieval acorde con la temática del juego.
b.	UI minimalista pero informativa, con indicadores visuales y efectos para mejorar la experiencia del jugador.

Elección del Game Engine
Motor de Juego: Godot
1)	Motor optimizado para juegos 2D con soporte nativo para pixel art.
2)	Lenguaje de programación GDScript, similar a Python, ideal para desarrollo rápido.
3)	Sistema de nodos que facilita la implementación de interfaces y mecánicas de juego.
4)	Soporte nativo para animaciones en 2D y efectos visuales mediante shaders.

Cronograma
Fase	        Duración	Actividades
Planificación	2 semanas	Documentación del proyecto, estructuración de mecánicas y diseño de niveles.
Desarrollo	4 semanas	Implementación del sistema de cartas, turnos y efectos en Godot.
IA y Balanceo	3 semanas	Desarrollo de inteligencia artificial para los enemigos y balanceo de dificultad.
Arte y Sonido	2 semanas	Creación de gráficos en pixel art, animaciones y efectos visuales.
Pruebas	        1 semanas	Depuración, optimización del rendimiento y pruebas de jugabilidad.

Diagramas de alto nivel para ilustrar el diseño de software
1)	Diagrama de arquitectura: Describe la estructura del código y cómo interactúan los diferentes sistemas (cartas, combate, interfaz).
2)	Flujo de juego: Ilustra la secuencia de eventos desde que el jugador inicia una partida hasta su finalización.
3)	Diagrama de lógica de combate: Representa cómo se procesan los turnos, ataques y efectos de estado. 
4)	Mapa del juego: Representará las rutas y encuentros que el jugador puede seguir a lo largo de su aventura.

Herramientas de Arte
•	Sprites y Texturas: Se utilizarán herramientas como Krita y Piskel para la creación de gráficos en pixel art. Krita es ideal para bocetos, retoques y diseños detallados, mientras que Piskel permite la edición precisa de píxeles y la animación cuadro por cuadro.
•	Animaciones: Godot cuenta con un potente sistema de animaciones 2D que permite interpolación de cuadros y uso de esqueletos 2D para movimientos más fluidos.
•	Sonido: Para la creación de efectos sonoros, se usarán herramientas como Bosca Ceoil para la música de fondo, Bfxr para efectos de sonido de estilo retro y Suno AI para generación de melodías adaptativas.

Escenarios y Ambientación
•	Escenarios en 2D: Los fondos serán diseñados en pixel art con efectos de paralaje para dar una sensación de profundidad y movimiento.
•	Iluminación dinámica: Se implementarán efectos de luces y sombras utilizando shaders en Godot, lo que permitirá generar un ambiente inmersivo y acorde con la temática oscura del juego.
•	Estilo visual: Inspirado en la estética gótica y medieval, con elementos visuales como ruinas, castillos y paisajes desolados, reforzando la sensación de un mundo decadente y peligroso.

Objetos y Terreno
Niveles
•	Nivel de praderas
•	Nivel de bosque
•	Nivel en el castillo
General:
•	Nubes
•	Pociones
•	Cartas
Praderas
•	Pasto
•	Pequeños animales
Bosque
•	Arboles
•	Troncos
•	Ramas
•	Hojas
•	Animales salvajes
Castillo
•	Casas
•	NPC

Detección de Colisiones, Físicas e Interacciones
•	Sistema de colisiones: Se utilizará el motor de físicas 2D de Godot para manejar la detección de colisiones entre los personajes, enemigos y objetos del entorno.
•	Interacción de cartas: Se implementará un sistema basado en eventos y efectos predefinidos, permitiendo que cada carta tenga una acción concreta dentro del combate.
•	Manejo de estados: Se agregarán buffs, debuffs y estados alterados (como veneno, congelación o regeneración) que modificarán la estrategia de los combates.

Lógica de Juego e Inteligencia Artificial
Reglas del juego: Implementación de un sistema de turnos donde los personajes actúan en orden de iniciativa, con restricciones de cartas y generación aleatoria de encuentros.
IA enemiga: Se usará un sistema basado en patrones de ataque y toma de decisiones condicionales, ajustándose al comportamiento del jugador.
Estrategias de enemigos: Se diseñarán diferentes tipos de enemigos con mecánicas únicas que obliguen al jugador a adaptar su estrategia en cada encuentro.

Networking (si aplica)
•	Si se implementa multijugador, se evaluará el uso de WebSockets o Godot Multiplayer API.
•	Se considerará la opción de partidas asíncronas entre jugadores para mantener la dinámica de turnos.

Audio y Efectos Visuales
•	Efectos de sonido: Creación de sonidos originales con Audacity y Bfxr, adaptados al estilo retro.
•	Música de fondo: Composiciones en Bosca Ceoil y Suno AI, enfocadas en melodías ambientales y temas de batalla épicos.
•	Efectos visuales: Uso de shaders y partículas en 2D para mejorar las animaciones de ataque, impacto y transiciones en combate.
•	Diálogos y narración: Se considerará la inclusión de efectos sonoros y voz en off para aumentar la inmersión del jugador.

Plataforma y Requerimientos de Software
Plataforma:
•	PC (Windows).
Requerimientos de hardware:
•	Mouse
•	Teclado
•	Monitor
•	Audifonos o Bocinas
•	Grafica
•	Disco duro

Este documento ira cambiando mediante el avance del proyecto