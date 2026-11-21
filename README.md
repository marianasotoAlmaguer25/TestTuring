# TestTuring
Proyecto donde simulamos la test de turing
simulación de la prueba de Turing con tres participantes, hecha para un proyecto final de la materia fundamentosIA

Un **juez** conversa al mismo tiempo con dos interlocutores, A y B. Uno es una **persona** conectada desde otro dispositivo y el otro es una **IA**. El servidor sortea en secreto, en cada ronda, quién es A y quién es B. Al terminar el tiempo, el juez indica cuál cree que es la máquina, y el sistema revela la respuesta y acumula estadísticas.

Si el porcentaje de aciertos del juez se acerca al 50%, la IA es difícil de distinguir de una persona.

## Cómo funciona

1. Una persona abre la página `/humano` y queda en espera.
2. El juez abre la página principal y pulsa "Comenzar ronda". Solo puede empezar si hay una persona conectada.
3. Cada pregunta del juez llega a los dos canales. La persona contesta a mano y la IA genera su respuesta.
4. La ronda dura 5 minutos por defecto. El juez puede votar antes, después de 2 preguntas.
5. Se muestra quién era la IA y el porcentaje acumulado de aciertos.
