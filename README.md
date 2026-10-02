Dynamic Swarm AI & Isometric Shooter Tech Demo
Este proyecto es una demostración técnica desarrollada en Unity 2022 con el objetivo de testear la integración de un sistema de pathfinding dinámico para enemigos en enjambre (Swarm AI). El prototipo está diseñado como un shooter de vista isométrica (top-down/isometric) inspirado en títulos como Dead Nation, enfocado en el comportamiento colectivo de la IA, evasión de obstáculos en tiempo real y físicas dinámicas.

🎯 Objetivos de la Prueba Técnica
Pathfinding Dinámico Avanzado: Navegación en tiempo real para un alto volumen de agentes simultáneos.
Comportamiento de Enjambre (Swarm/Flocking): Coordinación colectiva de los enemigos para rodear al jugador sin solaparse ni bloquearse.
Navegación Vertical y Evasión: Capacidad de los enemigos para sortear obstáculos dinámicos y realizar saltos entre plataformas para alcanzar al objetivo.
Seguimiento Impredecible: Algoritmo de persecución con variaciones en las rutas para evitar líneas de trayectoria completamente rectas, aumentando el reto y la inmersión.

🎮 Mecánicas de Juego y Controles
Vista e Inclinación: Cámara isométrica superior orientada a la acción rápida.
Movimiento del Jugador: Controles cardinales tradicionales en 8 direcciones (W, A, S, D).
Apuntado: Sistema Twin-Stick donde el personaje apunta e interactúa independientemente en la dirección del puntero del mouse.
Muerte Dinámica: Transición fluida de animaciones a físicas Ragdoll al eliminar enemigos, permitiendo reacciones de impacto creíbles.

🛠️ Detalles Técnicos y Requisitos
Motor: Unity 2022 (LTS)
Assets: Assets gratuitos integrados para prototipado rápido (modelos 3D, mapas de entorno y efectos visuales básicos).
Físicas: Colisionadores dinámicos, NavMesh / Custom Pathfinding y Rigidbody Ragdolls para los enemigos.
🚀 Instalación y Uso
Clonar el repositorio:
git clone https://github.com/tu-usuario/nombre-del-repositorio.git

Abrir en Unity:
Abre Unity Hub y añade el proyecto utilizando la versión Unity 2022.x.
Ejecutar Prototipo:
Abre la escena principal ubicada en Assets/Scenes/MainDemo.unity.
Entra en modo Play para probar el rendimiento del enjambre y el sistema de tiro.

📄 Licencia
Este proyecto fue desarrollado únicamente con fines de investigación, aprendizaje y pruebas técnicas. Los assets de terceros utilizados pertenecen a sus respectivos creadores dentro de sus licencias de distribución gratuita.
