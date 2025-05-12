# IA-Metodos-de-clasific
Desarrollo de una red neuronal para reconocimiento de imagenes. Para ello, vamos a trabajar con un dataset provisto por keras: CIFAR10. Este consta de 60000 imágenes en color de 32x32 en 10 clases, con 6000 imágenes por clase. Hay 50000 imágenes de entrenamiento y 10000 imágenes de prueba.

## CONCLUSIÓN
Observando los resultados obtenidos se puede concluir que, al realizar las arquitecturas de las redes neuronales los mejores resultados fueron obtenidos en funcion al aumento de neuronal y no tanto al aumento de layers, al tener gran cantidad de layers no se genero un aumento de la precision considerable como para generar ese gasto computacional.

Despues, en los Modelos CNN, como estos son una mejora de las arquitecturas anteriormente evaluadas, lo que se analizo es su eficiencia y si vale la pena implementarla considerando su gran costo computacional. Aqui se concluyó que hubo un aumento considerable llegando al 92%, siendo este suficientemente superior al 82% obtenido anteriormente, por lo tanto, se puede aceptar el costo computacional que conlleva utilizarlo, este funciona de una manera similar a las redes neuronales, cuanto mas neuronas por layers mejor rendimiento y mayor costo computacional obtenemos.

Por ultimo, se evaluo el modelo con otro dataset para analizar el Overfitting y se concluyó que, es un buen modelo en general, ya que, cambiando de dataset obtuvimos una precision del 83%, eso quiere decir que no existe Overfitting y que este Modelo CNN es bueno y se puede utilizar en diferentes dataset.
