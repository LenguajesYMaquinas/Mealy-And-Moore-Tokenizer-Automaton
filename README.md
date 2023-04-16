# Mealy And Moore Tokenizer Automaton TP3

- El programa debe estar separado por espacions, los elementos que no son espacios (aunque el espacio también genera el token *' '*) son los que pueden generar un token o más, se generará un token diferente a *R* si ese trozo de programa puede ser escrito en el lenguaje, así la secuencia del programa no tenga sentido. Por ejemplo, un trozo de programa valido es *a)* y uno no valido es *p;*

- Se debe añadir un pedazo de programa cualquiera adicional al final del programa para evitar omitir tokens en estados que responden en las transiciones.

- Es posible asignar a identificadores valores booleanos, por lo que es permitido escribir lineas del estilo: < IDENTIFICADOR > < := > < OPERADOR_COMPARACION > (< STRING > | < NUMBER >).

- El automata responde con el token *< R >* a todo lo que no es posible escribir en el lenguaje.

- Los parametros de la función pueden tener o no su tipo.

- La función debe tener obligatoriamente su tipo de retorno.

- Los tipos de datos disponibles son string, integer y boolean.

- Los valores para el tipo de dato *string* son (*'a'*..*'z'*)+.

- Los valores para el tipo de dato *integer* son (*'0'*..*'9'*)+.

- Los valores para el tipo de dato *boolean* son (*true*|*false*).

- Un programa vacio no es un programa valido.