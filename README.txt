El vector funciona de forma casi igual al ArrayList con la diferencia de que este está sincronizado, lo que significa que solo un hilo
es capaz de acceder al codigo a la vez, evitando problemas.

En el ejercicio no se ven este tipo de situaciones, por lo que es suficiente definir students como un vector en lugar de un ArrayList.

Luego de esto se crea un Vector para course de la forma: "private Vector<Student> students;" y el programa funciona igual que un Arraylist.

Al ser tan parecido al ArrayList, no es necesario dejar fijo un MAXIMUM_QUOTA para los estudiantes, ya que este es dinámico.