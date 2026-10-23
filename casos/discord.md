# Bot de subastas por puntos para Discord

## Problema y solución

Automatiza un sistema de puntos y subastas para una comunidad de juego: registra movimientos, reserva saldo comprometido en pujas, resuelve empates mediante desempate y aplica un ajuste semanal idempotente.

## Tecnologías

Python, discord.py y SQLite. Comandos slash, botones interactivos y tareas programadas. Es una automatización basada en reglas; no incorpora un modelo de lenguaje.

## Evidencia y alcance

El repositorio contiene pruebas de reglas de puntuación, saldos, historial, pujas, empates y ajuste semanal. El estado de la ejecución actual se registra en la entrega del repositorio de código; este caso no presupone su aprobación.

El código preparado para publicación excluye bases de datos, tokens, entornos virtuales e historial Git. La configuración usa variables de entorno. No se realiza ninguna operación contra Discord para preparar el portfolio.
