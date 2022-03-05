# scikit-learn
Objetivos de aprendizaje:
Para el final de este módulo, deberías ser capaz de:

Conocer los beneficios de usar una tubería
Usar una tubería para unir transformadores y estimadores
Nota: puedes mirar un video del paso a paso de este código al final de este módulo.

Introducción a las tuberías
Las tuberías son formas que tenemos para unir muchas tareas que usamos para modelar. En el módulo previo, predijimos el tipo de célula del cáncer de mamas, primero, escalando nuestra información, luego, aplicando el ACP y, finalmente, ejecutando nuestro modelo de regresión logística. ¡Esos son muchos pasos y eso significa mucho lugar para cometer errores!

Afortunadamente, sklearn tiene una solución para nosotros… ¡las tuberías!  Podemos poner todos los pasos en una tubería y, luego, ejecutarlo una vez. Esto minimiza las posibilidades de que podamos cometer errores y hace nuestros modelos más reproducibles.

Esto es especialmente útil para modelos donde necesitas escalar tu conjunto de datos antes de ejecutar un modelo, ¡ya que puede unir todos estos pasos! En este ejemplo, usaremos una tubería para escalar datos, aplicar el ACP y usar un modelo de regresión logística.  Exactamente los pasos que usamos en el módulo anterior.
