### Ejercicio 1 
#### Lista de Ingredientes

- El profesor Snape te ha encomendado una tarea muy importante: preparar una poción compleja para la clase de Pociones.
- Para ello, necesitas recolectar 3 ingredientes mágicos. Cada vez que encuentras un ingrediente en el Bosque Prohibido o en el invernadero de Herbología, debes agregarlo a los ingredientes.
    - Permitidos: Raíz de valeriana, Ojo de escarabajo y Pluma de hipogrifo
- Además, algunos ingredientes son peligrosos o están prohibidos, y deben ser ignorados si aparecen. Al final, tendrás que mostrar la lista final de ingredientes en _**orden alfabético**_ para que Snape pueda aprobar el trabajo.
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

            Informe ordenado de ingredientes encontrados: 
                    ["Pluma de hipogrifo", "Raíz de valeriana"]
                    
        *** Fin recoleccion ***
        ```



* Extra
    - Simular el buscar ingrediente en vez de mostrar un menu y generar el ingrediente aleatoriamente a partir de la posicion de un vector de ingredientes disponibles