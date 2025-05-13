### Ejercicio 2 
#### Defensa contra las artes oscuras

* Los Dementores son criaturas oscuras que se alimentan de la felicidad de las personas, dejándolas con recuerdos dolorosos y desesperación. Para protegerse de los Dementores, los estudiantes de Hogwarts aprenden el hechizo __*Patronus*__, que repele a estas criaturas y los aleja con recuerdos felices.
- En este ejercicio, simularemos un encuentro con un Dementor en un mini juego donde un estudiante debe lanzar el hechizo Patronus correctamente para repeler al Dementor y proteger su felicidad.
    - El juego tiene una cantidad definida de turnos
    - Cada intento consume 1 turno
    - Se necesitará ingresar correctamente el hechizo Patronus varias veces para vencer al Dementor, dependiendo de la vida que tenga. 
    - Si el estudiante no ingresa el hechizo correctamente el Dementor consumirá su felicidad y recuerdos felices, acercándose más a la derrota del estudiante en caso de llegar a cero dichos puntos de cordura.
        - Si el estudiante ingresa bien los hechizos y logra vencer al dementor entonces se mostrar un mensaje de victoria
        - Si ninguno de los dos fue derrotado el resultado final es empate

- Posible configuracion para la simulacion
    * Vida maxima del dementor: 1000
    * Vida maxima del estudiante: 350
    * Daño, por turno perdido, del dementor al estudiante: 75
    * Daño, por hechizo acertado, del estudiante al dementor: 267
    * Turnos totales: 5 
    
    - Posible resultado visual del programa
        -   ```
            *** Iniciar simulacion ***

            Turnos restantes: 5
            estudiante: 350 / dementor: 1000
                Usa el hechizo!
            Patrnus
            Fallaste: 75 daño recibido
            -------------------------------
            Turnos restantes: 4
            estudiante: 275 / dementor: 1000
                Usa el hechizo!
            Patronus
            Acertaste: 267 infligido al dementor
             -------------------------------
            Turnos restantes: 3
            estudiante: 275 / dementor: 733
                Usa el hechizo!

            ...
            ```
<br>
<br>
<br>

1. Extra
    - Permitir lanzar minimo 2 hechizos diferentes
        - El segundo hechizo lanza el doble de daño pero tiene un 70% de probabilidad en fallar
1. Extra
    - Permitir que el dementor realice un doble ataque de forma aleatoria en cada turno con un 5% de probabilidad
        - Adicional: regular el doble ataque cada 2 turnos