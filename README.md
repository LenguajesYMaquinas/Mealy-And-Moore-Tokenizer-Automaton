# Mealy And Moore Tokenizer Automaton TP3

- Los parametros de la función pueden tener o no su tipo.

- La función debe tener obligatoriamente su tipo de retorno.

- Los tipos de datos disponibles son string, integer y boolean.

- Los valores para el tipo de dato *string* son (*'a'*..*'z'*)+.

- Los valores para el tipo de dato *integer* son (*'0'*..*'9'*)+.

- Los valores para el tipo de dato *boolean* son (*true*|*false*).

- El programa debe tener una función y opcionalmente más de una.

- Un programa vacio no es un programa valido.

- El automata toma solo el primer camino posible para generar un token. Por ejemplo, para la palabra *bend* el automata se toma el camino para llegar a la palabra begin, pero al no completarse la palabra, el automata responde con el token de string, aunque dentro de esa cadena se encuentre la subcadena *end*, de la cual se podría generar un token.