# **LAII**

# Analizador Léxico de Expresiones Matemáticas
Este es un analizador léxico de expresiones matemáticas con una interfaz gráfica en Java. Permite a los usuarios ingresar una expresión matemática que puede contener variables (w, x, y, z), constantes (pi, e), números (0-9) y operadores (+, -, /, *).

# Características
## Interfaz Gráfica: 
La aplicación cuenta con una interfaz gráfica amigable que permite a los usuarios ingresar expresiones matemáticas de forma sencilla.

## Botón "Analizar": 
La interfaz incluye un botón "Analizar" que, al ser presionado, ejecutará el analizador léxico sobre la expresión ingresada y mostrará los resultados en una tabla o área de texto.

## Clasificación de Tokens: 
El analizador léxico clasificará cada token de la expresión en uno de los siguientes tipos:
- Variable
- Constante (pi, e)
- Número
- Operador (+, -, /, *)
- Desconocido (si no puede clasificar un token)
- 
## Resultados Detallados: 
Los resultados se mostrarán en una tabla o área de texto y proporcionarán información sobre el tipo de cada token, permitiendo a los usuarios comprender cómo se clasificaron los elementos de la expresión.

## Resumen de Coincidencias: 
En otra sección de la interfaz, se mostrará un resumen de las coincidencias encontradas en la expresión matemática. Este resumen incluirá información sobre la cantidad de:
- Números
- Variables
- Constantes
- Tokens desconocidos encontrados en la expresión.

# Uso
1. Ejecute la aplicación.

2. Ingrese una expresión matemática en el campo de texto proporcionado.

3. Haga clic en el botón "Analizar".

4. Los resultados del análisis léxico se mostrarán en una tabla o área de texto en la interfaz.

5. Revise el resumen de coincidencias para obtener información sobre la composición de la expresión ingresada.

# Ejemplo
Si ingresa la expresión matemática: "x + 2 * pi - y / 5", el analizador léxico mostrará los siguientes resultados:

| Tipo        | Valor   |
|-------------|---------|
| Variable    | x       |
| Operador    | +       |
| Número      | 2       |
| Operador    | *       |
| Constante   | pi      |
| Operador    | -       |
| Variable    | y       |
| Operador    | /       |
| Número      | 5       |

Resumen de coincidencias:
- 2 NUMEROS
- 4 OPERADORES
- 1 CONSTANTE
- 2 VARIABLES
- 0 DESCONOCIDOS
  
# Contribuciones
¡Contribuciones son bienvenidas! Si desea mejorar este analizador léxico de expresiones matemáticas, no dude en crear un "pull request" o reportar problemas en la sección de "Issues".
