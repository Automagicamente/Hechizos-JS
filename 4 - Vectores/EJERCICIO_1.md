### Ejercicio 1 
#### Lista de Ingredientes

- El profesor Snape te ha encomendado una tarea muy importante: preparar una poción compleja para la clase de Pociones.
- Para ello, necesitas recolectar 3 ingredientes mágicos, minimo 2. Cada vez que encuentras un ingrediente en el Bosque Prohibido o en el invernadero de Herbología, debes agregarlo a los ingredientes.
    - Permitidos: Raíz de valeriana, Ojo de escarabajo y Pluma de hipogrifo
- Además, algunos ingredientes son peligrosos o están prohibidos, y deben ser ignorados si aparecen.
    - No permitidos: Mandrágora negra o Sangre de dragón

* Posible resultado del programa
    -   ```
        *** Iniciando recoleccion ***

            Que ingrediente encontraste?
                1 - Raíz de valeriana
                2 - Mandrágora negra 
                3 - Pluma de hipogrifo
                4 - Ojo de escarabajo 
                5 - Sangre de dragón

            1
            Ingrediente aceptado!
                
            Que ingrediente encontraste?
                1 - Raíz de valeriana
                2 - Mandrágora negra 
                3 - Pluma de hipogrifo
                4 - Ojo de escarabajo 
                5 - Sangre de dragón

            2
            Ingrediente NO aceptado, cuidado!

            Que ingrediente encontraste?
                1 - Raíz de valeriana
                2 - Mandrágora negra 
                3 - Pluma de hipogrifo
                4 - Ojo de escarabajo 
                5 - Sangre de dragón

            3
            Ingrediente aceptado!

        *** Fin recoleccion ***

            Informe de ingredientes encontrados: 
                    ["Raíz de valeriana", "Pluma de hipogrifo"]

            Resulado: Aprobado!            
        ```



* Extra
    - Mostrar la lista final de ingredientes en _**orden alfabético**_ 
- Extra 2
    - Simular el buscar ingrediente, en vez de mostrar un menu, generandolo aleatoriamente a partir de la posicion de un vector de ingredientes disponibles