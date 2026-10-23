# Truco · Reglas y multijugador

## Problema y solución

Proyecto de videojuego en desarrollo que modela reglas del Truco y sincroniza partidas entre clientes. Permite mostrar un problema de software diferente al de un sitio web: estados, turnos, reglas, mensajes y recuperación de conexión.

## Tecnologías y decisiones

C#/.NET, Godot y WebSocket. Separación entre motor de reglas, servidor y cliente visual. Las pruebas de reconexión comprueban que un jugador recupere el estado de la partida.

## Desarrollo con IA

Uso de asistencia de IA para construir e iterar reglas, herramientas, clientes y verificaciones. En una entrevista puedo recorrer una decisión y contrastarla con su prueba, sin presentar el código generado como evidencia de dominio autónomo de todas las tecnologías.

## Evidencia histórica

El informe del 12 de agosto de 2026 registra 683 pruebas .NET aprobadas y cinco partidos de validación automatizada mediante un túnel público, incluyendo desconexión y reconexión. También registra tres partidas E2E con cuatro procesos Godot.

Los procesos se ejecutaron en la misma máquina: esto no equivale a un playtest con cuatro personas en redes distintas. No se repitieron esas pruebas para esta presentación.

## Límites

Proyecto en desarrollo. Sin servidor público persistente verificado. No se distribuyen código privado, ejecutables ni recursos gráficos de terceros. Las cifras corresponden a la fase documentada, no a todas las versiones posteriores.
